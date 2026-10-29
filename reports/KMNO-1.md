# KMNO en Solana: reporte de respaldo para el bounty de RaptorX

**Fecha de consulta:** 28-10-2026, UTC. **Activo:** Kamino, ticker KMNO. **Estado de RaptorX:** en captura.

Este es un análisis externo con fuentes públicas, no un reporte generado dentro de RaptorX. Si lo usas en el submission, identifícalo como respaldo y no como prueba de una interacción con su IA. El brief exige un reporte generado en la plataforma, una pregunta pertinente y capturas legibles de ambos.[17]

## Resumen en tres líneas

Kamino combina préstamos, liquidez y apalancamiento en Solana; KMNO permite staking con beneficios de puntos y su documentación plantea la gobernanza de forma condicional.[2][11]
La API de CoinGecko reportó un precio de **USD 0,03878302**, capitalización de **USD 227.488.605** y volumen de **USD 8.308.888** en la ventana móvil de 24 horas; DeFiLlama registró **USD 1.334.322.110** de TVL agregado, con otro horario de actualización.[13][15]
El próximo desbloqueo reportado es el **30-10-2026**, por aproximadamente **229,17 millones de KMNO**; el porcentaje efectivamente bloqueado y la presencia operativa de este mint en RaptorX siguen sin verificarse de manera suficiente.[2][10][7]

## Qué es Kamino y qué representa KMNO

Kamino ofrece préstamos y depósitos de activos, estrategias automatizadas de liquidez y productos con apalancamiento en Solana.[2]
No confundas el negocio del protocolo con la demanda de su token: una persona puede usar sus mercados sin que eso demuestre una compra neta de KMNO.[2]

El mint de referencia es **`KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS`**.[13]
CoinGecko lo identifica bajo Solana y Solscan lo muestra como Kamino.[13][9]
Ese identificador, no solo el ticker, debe coincidir en cualquier captura de RaptorX.[13][9]

La utilidad documentada de KMNO es el staking para potenciar la obtención de puntos.[11]
La sección de gobernanza dice que, si se lanza la gobernanza del protocolo, KMNO sería su token principal para decisiones sobre incentivos, grants, asignación de ingresos y ciertos aspectos de riesgo.[11]
Esa redacción no acredita por sí sola una gobernanza ya activa ni un derecho automático a recibir ingresos.[11]

## Tokenomics: oferta, circulación, holders y distribución

| Dato | Resultado | Fuente y alcance |
|---|---|---|
| Oferta total planificada | 10.000.000.000 KMNO | Documentación oficial.[1]
|
| Oferta máxima informada | 10.000.000.000 KMNO | API de CoinGecko.[13]
|
| Oferta actual del explorador | 9.999.956.616,198987 KMNO | Campo `Current Supply` de Solscan; no equivale a circulación.[9]
|
| Oferta circulante | 5.863.698.998,5 KMNO | API de CoinGecko, actualización del dato: 28-10-2026 a las 18:58:49 UTC.[13]
|
| Circulante respecto de la oferta planificada | 58,64 % | Cálculo: circulante dividido por oferta planificada; redondeado.[13][1]
|
| Complemento no circulante | 41,36 % | Cálculo respecto de la oferta planificada. **No es una medición de tokens bloqueados**.[13][1]
|
| Circulante inicial del lanzamiento | Aproximadamente 1.000.000.000 KMNO | Dato histórico, no oferta circulante actual.[1]
|
| Lanzamiento del token | 30-04-2024 | Fecha oficial del evento génesis.[1]
|
| Holders actuales | **No verificado** | La extracción de Solscan dejó el campo sin un valor utilizable; el acceso directo y el navegador encontraron una verificación de seguridad.[9]
|
| Concentración de mayores holders y beneficiarios finales | **No verificado** | No se obtuvo una tabla actual de saldos con etiquetas de exchanges, staking y tesorería. |

La asignación inicial oficial es la siguiente.[1]
No representa la distribución actual entre wallets.[1]

| Grupo | Asignación | Condición publicada |
|---|---|---|
| Comunidad y grants | 35 % | Incentivos y apoyo a desarrolladores administrados por la tesorería.[1]
|
| Stakeholders y asesores | 35 % | Bloqueo inicial de 12 meses y vesting lineal posterior de 24 meses.[1]
|
| Contribuidores principales | 20 % | Bloqueo inicial de 12 meses y vesting lineal posterior de 24 meses.[1]
|
| Liquidez y tesorería | 10 % | Desarrollo de liquidez del token.[1]
|

El evento génesis distribuyó un **7,5 %** de la oferta total dentro de la asignación de comunidad y grants.[1]
No lo sumes otra vez a la tabla. Stakeholders, asesores y contribuidores representan conjuntamente un **55 %** de la asignación inicial, calculado a partir de la documentación; eso no demuestra que hoy controlen ese mismo porcentaje líquido.[1]

## Desbloqueos: calendario, próximo evento y porcentaje bloqueado

**Base oficial:** stakeholders, asesores y contribuidores tienen un bloqueo de 12 meses, seguido por vesting lineal durante 24 meses.[1]
La documentación consultada no entrega una conciliación actual por wallet de cuánto permanece bloqueado.[1][11]

| Elemento | Evidencia consultada | Lectura para el análisis |
|---|---|---|
| Próximo evento | 30-10-2026, según Tokenomics.com; CoinGecko coincide en el 30 de octubre.[10][2]
| Fecha reportada por proveedores, no ejecución on-chain ya ocurrida. |
| Monto | 229.166.667 KMNO en Tokenomics.com; CoinGecko lo redondea a 229,17 millones.[10][2]
| Orden de magnitud coincidente. |
| Destinatarios | CoinGecko informa 145,83 millones para stakeholders y asesores, y 83,33 millones para contribuidores.[2]
| Cifras redondeadas del proveedor; el desglose no debe tratarse como transferencias verificadas. |
| Tamaño relativo | 2,29 % de la oferta planificada y 3,91 % del circulante de referencia.[10][13][1]
| Cálculos propios redondeados con los datos capturados. |
| Valor nocional al precio de referencia | Aproximadamente USD 8.887.775.[10][13]
| Monto de tokens multiplicado por USD 0,03878302. No es valor de venta ejecutable. |
| Fechas posteriores visibles | 30-11-2026, 30-12-2026 y 30-01-2027; el proveedor declara término el 30-03-2027.[10]
| Calendario del proveedor, no conciliación contractual completa. |
| Porcentaje efectivamente bloqueado | **No verificado**.[10]
| No uses el complemento del circulante como sustituto. |

**Conflicto que debes conservar:** Tokenomics.com declara simultáneamente un **42,2 %** bloqueado, equivalente a **4.224.999.998 KMNO**, y **1.375.000.002 KMNO** pendientes en los eventos futuros que enumera.[10]
Además, presenta **1.000.000.000 KMNO** como circulante actual, frente a **5.863.698.998,5 KMNO** en la API de CoinGecko.[10][13]
Por esa inconsistencia, este reporte no valida su porcentaje bloqueado ni toma su calendario como un inventario completo de todo el supply.[10][13]

Un desbloqueo permite disponer de tokens según sus condiciones; no prueba que todos entren inmediatamente a exchanges o sean vendidos.[10]
Para estudiar presión vendedora faltan transferencias de las wallets receptoras y profundidad ejecutable del mercado, no solo el calendario.[10]

## Liquidez: TVL, pools DEX y dónde se negocia

### Capital del protocolo

La API de DeFiLlama reportó **USD 1.334.322.110** de TVL para Kamino, con timestamp del dato **28-10-2026 a las 18:03:11 UTC**.[15]
El componente Kamino Lend registró aproximadamente **USD 1.262.710.904**, redondeado, con timestamp **17:48:59 UTC**.[16]
El agregado y el componente no se suman.[15][16]

El TVL del protocolo no es liquidez de compraventa de KMNO.[15][14]
Además, la página de DeFiLlama indica que su TVL predeterminado excluye préstamos activos, mientras el campo de metodología de su API de Lend contiene una descripción distinta sobre préstamos contabilizados.[3][16]
Aquí se mantienen las categorías separadas y no se construye un TVL alternativo sumándolas.[3][16]

### Pools del token

La consulta por el mint exacto a DEX Screener devolvió **30 pares únicos**.[14]
La suma de `liquidity.usd` de esa respuesta fue **USD 2.453.366,89** y la de `volume.h24`, **USD 3.285.949,45**.[14]
Son cálculos sobre esa respuesta, no un censo exhaustivo de todos los pools ni el volumen global del token.[14]

| Pool y DEX | Dirección del pool | Liquidez informada, USD | Volumen 24 h, USD |
|---|---|---:|---:|
| KMNO/USDC, Orca | `3ndjN1nJVUKGrJBc1hhVpER6kWTZKHdyDrPyCJyX3CXK` | 1.971.006,33 | 3.090.399,10 |
| KMNO/JitoSOL, Orca | `2nJjE2ba3iGtefN4UNM1KN5FdYCwssU4Bzhc8URceqh6` | 268.646,49 | 131.649,39 |
| KMNO/SOL, Meteora | `5LziHU8Z1iKadAmPFWQi2Rn2MvTvXYKVFt1ZDevbvKFx` | 47.130,42 | 3.786,97 |
| KMNO/SOL, Orca | `5E2cHo3DQnRjB3zWHKUs86RPqCeLboMgKV9WjxFwUjhV` | 46.765,00 | 36.360,81 |
| KMNO/SOL, Raydium | `6tpEjdVoV7spGbE4RdXNxmRXbw4wb5ouLupDWpLYZyNH` | 38.935,08 | 5.057,66 |

Todos los valores de la tabla provienen de la respuesta de DEX Screener capturada el **28-10-2026 a las 18:59:45 UTC**.[14]

El pool KMNO/USDC de Orca concentra **80,34 %** de la liquidez informada en la muestra, calculado por pool y sin inferir propiedad de los fondos.[14]
Esa concentración no equivale a profundidad disponible cerca del precio: no se capturaron ticks, cotizaciones de ejecución ni un análisis de slippage.[14]

CoinGecko también muestra mercados spot en Binance, OKX y Bybit, entre otros, además de Orca.[2]
Su tabla de mercados mezcla actualizaciones que no coinciden exactamente con su resumen; por eso se usa para acreditar lugares de negociación, no para reemplazar el precio de referencia de la API.[2]

## Demanda y uso: préstamos, ingresos y usuarios

| Métrica | Resultado | Fuente |
|---|---:|---|
| Préstamos activos del agregado Kamino | USD 861.676.808 | API de DeFiLlama; categoría `borrowed` separada del TVL.[15]
|
| Comisiones del agregado, últimos 30 días | USD 4,82 millones | Página de DeFiLlama.[3]
|
| Ingresos del agregado, últimos 30 días | USD 623.535 | Página de DeFiLlama.[3]
|
| Ingresos del agregado, últimas 24 horas | USD 19.138 | Página de DeFiLlama.[3]
|
| Ingresos acumulados del agregado | USD 51,25 millones | Página de DeFiLlama.[3]
|
| Ingresos de Kamino Lend, últimos 30 días | USD 604.908 | Componente del agregado, no monto adicional para sumar.[4]
|
| Ingresos a holders, últimos 30 días | USD 0 | Categoría `Holders Revenue` registrada por DeFiLlama.[3]
|
| Usuarios o direcciones activas actuales | **No verificado** | No se obtuvo una serie actual con definición y ventana comparables. |

Las métricas de comisiones e ingresos de las páginas se consultaron a las **19:00 UTC del 28-10-2026**; no tienen el mismo timestamp explícito de la API de precios.[3][4]

La evidencia acredita actividad económica del protocolo, pero no una transmisión automática a KMNO.[3][11]
El staking con beneficios de puntos es una utilidad documentada; el ingreso distribuido a holders aparece en cero en la categoría consultada.[11][3]
Eso no equivale a probar que nunca exista otra modalidad de incentivos, recompra o beneficio: esas modalidades no se verificaron aquí.[11][3]

No presentes transacciones de un pool DEX, holders del token y usuarios activos del protocolo como si fueran la misma métrica. Este reporte deja el último dato pendiente en lugar de reemplazarlo por una aproximación sin respaldo.

## Trading: precio, volumen y capitalización

Se adopta una sola respuesta de la API de CoinGecko como referencia para evitar mezclar widgets con distintos horarios.[13]
Su `last_updated` es **2026-10-28T18:58:49.000Z**; se descargó a las **18:59:45 UTC**.[13]

| Métrica | Valor de referencia |
|---|---:|
| Precio por KMNO | USD 0,03878302 |
| Variación de precio en 24 horas | -2,55898 % |
| Volumen global de negociación en 24 horas | USD 8.308.888 |
| Capitalización circulante | USD 227.488.605 |
| Valoración totalmente diluida, FDV | USD 387.959.235 |

Los valores son campos reportados por CoinGecko, no una estimación de ejecución de órdenes ni una recomputación de capitalización a partir de cifras de otras fuentes.[13]

Como contraste, DEX Screener informó **USD 0,03881** en el pool KMNO/USDC de Orca al momento de su consulta.[14]
No se promedian ambos precios: uno es la referencia agregada y otro corresponde a un pool concreto.[14]

## Presencia de KMNO en RaptorX

**Estado: en captura. Listado operativo del mint de Kamino: no verificado. Reporte de IA e intercambio de preguntas dentro de RaptorX: no verificados en este paquete.**

La evidencia local [`kmno_captura_1.json`](kmno_captura_1.json), fechada por su propio campo `ts_utc` el **28-10-2026 a las 17:53:47 UTC**, registra que `https://raptorx.trade/solana/KMNO` respondió con el mensaje de que no pudo cargar el token desde la URL.[7]
KMNO tampoco figura entre las filas del screener incluidas en esa captura.[7]

Una extracción pública posterior no permitió confirmar de forma consistente la página del mint correcto; el último intento guardado devolvió un error de extracción.[7]
La búsqueda pública tampoco entregó una prueba suficiente de listado. **No encontrarlo en esa muestra no demuestra que RaptorX no lo soporte:** puede faltar otra ruta, una búsqueda por mint o la generación autenticada del reporte.[7]

No atribuyas a RaptorX las cifras de CoinGecko, DeFiLlama o DEX Screener que aparecen arriba. Para cerrar este pendiente necesitas una captura legible de la página correcta, el reporte generado en RaptorX y la pregunta con su respuesta dentro de la plataforma.[17]

## Riesgos principales

1. **Dilución y concentración inicial.** El desbloqueo reportado representa aproximadamente 3,91 % del circulante de referencia; las asignaciones iniciales de stakeholders y contribuidores suman 55 %.[10][13][1]
Puede existir presión vendedora, pero falta verificar destinatarios, transferencias y ventas efectivas.[10][13][1]
2. **Captura de valor del token.** Uso y revenue del protocolo no implican dividendos para KMNO.[3][11]
La categoría de ingresos a holders consultada registra cero y la documentación de gobernanza es condicional.[3][11]
3. **Liquidez de mercado concentrada.** Un pool concentra 80,34 % de la liquidez de la muestra DEX.[14]
El TVL de Kamino no respalda la salida de una orden de KMNO; falta medir profundidad y slippage antes de inferir capacidad de absorción.[14][15]
4. **Riesgo técnico, de crédito y de liquidez del protocolo.** Kamino reconoce riesgos de contratos y mercados de préstamo, pérdidas por deuda incobrable, decisiones de curadores y demoras de retiro cuando los fondos prestados no están disponibles.[19]
El apalancamiento también puede aumentar pérdidas y exposición a tasas variables.[19][20]
5. **Riesgo de calidad de evidencia.** Hay proveedores con datos internos contradictorios de supply bloqueado, campos de holders no recuperados y una captura incompleta de RaptorX.[10][9][7]
Una conclusión de inversión o un submission que oculte esas brechas sería más fuerte que la evidencia disponible.[10][9][7]

## Alcance para el bounty y pendientes

El detalle público de Superteam confirma una bolsa total de **125 USDC**, repartida en **75 USDC** para el primer lugar y **50 USDC** para el segundo.[17]
El cierre figura como **2026-11-02T03:59:59.000Z** y el acceso permite agentes mediante `AGENT_ALLOWED`.[17]
No son 125 USDC garantizados para cada participante.[17]

Si usas este documento para preparar el README y `otherInfo`, conserva esta separación:

- **Comprobado externamente:** identidad del mint, utilidad documentada, asignación inicial, referencia de mercado, TVL, préstamos, ingresos y pools consultados.
- **Reportado por proveedores, con límites:** evento de desbloqueo y su calendario. Porcentaje efectivamente bloqueado: **no verificado**.
- **Pendiente:** holders y concentración actuales, usuarios activos con definición reproducible, profundidad ejecutable y evidencia propia del reporte y conversación en RaptorX.

No se publicó este documento ni se envió una participación. Los datos por campo y sus URLs están en [`KMNO-1-data.md`](KMNO-1-data.md). Las respuestas descargadas, errores y cálculos reproducibles están en [`evidencia-KMNO-1/`](evidencia-KMNO-1/). Este análisis no es una recomendación de compra o venta.

## Fuentes

[1] https://kamino.com/docs/kmno
[2] https://www.coingecko.com/en/coins/kamino
[3] https://defillama.com/protocol/kamino
[4] https://defillama.com/protocol/kamino-lend
[7] https://raptorx.trade/solana/KMNO
[9] https://solscan.io/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
[10] https://app.tokenomics.com/tokenomics/kamino/unlocks
[11] https://kamino.com/docs/kmno/token-info
[13] https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
[14] https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
[15] https://api.llama.fi/protocol/kamino
[16] https://api.llama.fi/protocol/kamino-lend
[17] https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
[19] https://kamino.com/docs/products/lending-vaults/risks.md
[20] https://kamino.com/docs/products/multiply/risks.md
