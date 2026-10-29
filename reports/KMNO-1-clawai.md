# KMNO: reporte de IA generado dentro de RaptorX (Claw AI 5.0) + hallazgo de calidad de datos

**Capturado:** 29-10-2026, ~03:10 UTC (reporte fechado "10/29/2026 12:11 AM"). **Activo:** Kamino (KMNO), Solana.
**Método:** flujo atómico en `browser_exec` con `local=True` (login → Claw AI 5.0 → prompt → espera → extracción en una sola llamada), porque las sesiones backend con `use_real_profile` caían por CDP. Ver `RECIPE.md` y la lección en la skill `browser-exec-sessions`.

Este documento **cierra el pendiente** que `KMNO-1.md` dejaba abierto (líneas 5 y 186): "el reporte generado en RaptorX y la pregunta con su respuesta dentro de la plataforma".

## La pregunta enviada a Claw AI 5.0

> "Genera el Alpha report del token KMNO en Solana (mint KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS): precio, niveles clave, volumen, liquidez y plan de trade corto."

El reporte completo generado in-platform está en [`KMNO-clawai-full.txt`](../KMNO-clawai-full.txt) (37.698 bytes, 1060 líneas). Capturas legibles: `cap-09-kmno-report-LOCAL.png` (estado post-login) y `cap-13-kmno-full.png` (reporte).

## Datos que dio Claw AI 5.0 (tal cual, sin recomputar)

| Métrica | Claw AI 5.0 | Fuente que cita Claw AI |
|---|---:|---|
| Precio | $0.02450 USD | DexScreener / CoinGecko |
| Market cap | $131.2M (DexScreener) / $133.5M (CoinGecko) | ambos |
| FDV | $244.91M | CoinGecko |
| Volumen 24 h | $1.23M (par Orca) / $5.09M (todos los pares) | ambos |
| TVL | $1,403,004,211 (~$1.4B) | DeFiLlama |
| Mcap/TVL | 0.10 | calculado |
| Liquidez (Orca KMNO/USDC) | $1,450,285 | DexScreener |
| Oferta circulante | 5,449,315,399 KMNO (~54.5%) | — |
| Oferta total | 10,000,000,000 KMNO | — |
| ATH | $0.247842 (15-12-2024) → -90.11% | CoinGecko |
| Tendencia | 1h +0.28% · 6h -0.19% · 24h +1.35% · 7d -9.82% · 14d +10.39% · 30d +32.88% · 60d +28.18% · 200d -29.91% · 1y -55.09% | — |
| Flujo de órdenes | 9.190 compras vs 8.812 ventas (24h); buy ratio 24h 51%, 1h 52% | — |
| Rank CoinGecko | #223 | — |
| Listados | Binance, Coinbase, Kraken, Bybit, OKX, KuCoin, Gate.io, Bitget, MEXC, Upbit, Bithumb + DEX (Orca, Meteora, Raydium) | — |
| Sentimiento | Comunitario positivo; "Kamino is winning. The token isn't." (producto fuerte, token con poca captura de valor); Q2'26: revenue $1.84M (-10.6% QoQ), deposits $2.29B (-21.1%), buyback $0 | X/foros |

## Hallazgo clave: el precio de Claw AI está desfasado ~35% de la fuente autoritativa

Consulta en vivo a la API de CoinGecko (**29-10-2026, ~03:10 UTC**, `api.coingecko.com/api/v3/coins/kamino`):

| Fuente | Momento | Precio USD | Mcap USD |
|---|---|---:|---:|
| `KMNO-1-data.md` (CoinGecko API) | 28-10 18:59Z | 0.03878302 | 227.488.605 |
| **CoinGecko en vivo (verificado ahora)** | 29-10 ~03:10Z | **0.03768491** | **220.966.528** |
| Reporte Claw AI 5.0 | 29-10 00:11Z | 0.02450 | 131–133.5M |

Lectura:
- El precio real (CoinGecko autoritativo) está en **~$0.0377**. Mi captura de `KMNO-1-data.md` coincide con esa fuente (deriva normal de horas).
- El reporte Claw AI da **$0.02450**, ~35% por debajo. Es internamente consistente (sus mcap/FDV/tendencias derivan de ese precio), pero **no está alineado con CoinGecko en vivo**.
- Causa probable: Claw AI usa un feed de precio propio o un par DEX concreto (o una caché desfasada), no el agregado de CoinGecko. No es una caída de 35% en 5 horas (el chg 7d de CoinGecko es -10.4%, no -35%).

**Regla de uso (no maquillar):** para **niveles absolutos** (precio, mcap, volumen) usar CoinGecko en vivo (`0.0377` / `$221M`). Para **estructura, sentimiento, flujo de órdenes, narrativa y riesgos** usar el reporte Claw AI. No mezclar los dos conjuntos como si fueran el mismo snapshot. Esto refuerza el riesgo #5 de `KMNO-1.md` ("calidad de evidencia").

## Plan de trade corto (síntesis, no recomendación)

Basado en CoinGecko en vivo + estructura de Claw AI. Solo si se opera con capital propio y riesgo acotado.

- **Tendencia de fondo:** bajista a 1 año (-55%) y 200d (-29.9%), pero con rebote de 30 días (Claw AI +32.9%; CoinGecko 30d -9.8% → las dos fuentes no coinciden, ver hallazgo). En corto plazo hay flujo comprador leve (buy ratio 51-52%).
- **Catalizador/riesgo concreto:** desbloqueo reportado el **30-10-2026** por ~229,17M KMNO (~3.9% del circulante). Es el evento que domina la semana: riesgo de presión vendedora si las wallets receptoras venden.
- **Zonas de referencia (a re-verificar en vivo antes de operar):**
  - Soporte: cerca del ATL de jun-2026 (~$0.0134 según Claw AI) y el mínimo reciente; usar el gráfico en vivo.
  - Resistencia: el rango del rebote de 30 días.
- **Postura sugerida:** neutral con sesgo defensivo alrededor del desbloqueo. No entrar largo agresivo el 30-10 sin ver cómo se absorbe el desbloqueo; si se absorbe sin caída, recién entonces considerar largo con stop bajo el soporte. Tamaño pequeño: liquidez de mercado concentrada en un pool (~80% en Orca KMNO/USDC).
- **Gestión:** stop bajo el soporte de la velas; objetivo la resistencia del rebote; no promediar a la baja si el desbloqueo rompe el soporte.

## Qué cierra y qué queda

- **Cierra (bounty):** ahora hay (a) la pregunta enviada, (b) el reporte generado en la plataforma (Claw AI 5.0), (c) capturas legibles de ambos. El requisito del brief de RaptorX queda cubierto con evidencia propia.
- **Queda:** publicar el submission (README + `otherInfo` + capturas) en la lista de Superteam `raptorx-research-challenge-ask-better-questions-find-better-alpha` (cierre 2026-11-02T03:59:59Z, bolsa 125 USDC: 75 primer + 50 segundo). El submission ya se registró antes (ID `df81978b-...`); falta confirmar que incluya el reporte Claw AI y las capturas finales.
- **Reforzar:** el hallazgo de desfase de precio hace que el submission sea más fuerte si se **declara** la discrepancia (Claw AI vs CoinGecko) en vez de ocultarla: demuestra lectura de calidad de datos, que es justo lo que el brief premia ("ask better questions, find better alpha").
