# KMNO: datos capturados y procedencia

Cada línea conserva un dato, su unidad o estado y la URL de origen. Los decimales con punto en valores API preservan la representación de la respuesta. Los campos calculados se distinguen de los capturados. Las ventanas de 24 horas y 30 días son móviles, salvo que el proveedor indique otra definición.

## Identidad, mercado y oferta
- Mint de Solana = KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Actualización del dato = 2026-10-28T18:58:49.000Z | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Consulta HTTP = 2026-10-28T18:59:45.142716+00:00 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Precio USD = 0.03878302 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Capitalización circulante USD = 227488605 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Volumen 24 h USD = 8308888 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- FDV USD = 387959235 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Variación precio 24 h % = -2.55898 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Oferta circulante KMNO = 5863698998.5 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Oferta total informada KMNO = 9999956616.198988 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Oferta máxima informada KMNO = 10000000000.0 | fuente=API CoinGecko | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Oferta total planificada KMNO = 10,000,000,000 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Oferta circulante inicial KMNO = ~1,000,000,000 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Fecha TGE = April 30, 2024 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Comunidad y grants % = 35 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Stakeholders y asesores % = 35 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Contribuidores principales % = 20 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Liquidez y tesorería % = 10 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Génesis, incluido en comunidad y grants % = 7.5 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Bloqueo inicial de stakeholders y contribuidores, meses = 12 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Vesting lineal posterior, meses = 24 | fuente=documentación oficial | https://kamino.com/docs/kmno
- Oferta actual del explorador KMNO = 9,999,956,616.198987 | campo=Current Supply; consulta=2026-10-28T19:00:30Z | https://solscan.io/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Holders actuales = no verificado | campo sin valor en extracción; curl=403; navegador=verificación de seguridad | https://solscan.io/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Concentración actual de mayores holders = no verificado | sin tabla de saldos y etiquetas | https://solscan.io/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Oferta circulante respecto de planificada % = 58.636989985 | calculado=circulating_supply/10000000000*100 | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false ; https://kamino.com/docs/kmno
- Complemento no circulante respecto de planificada % = 41.363010015 | calculado=(10000000000-circulating_supply)/10000000000*100; no equivale a bloqueado | https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false ; https://kamino.com/docs/kmno
- Stakeholders más contribuidores, asignación inicial % = 55 | calculado=35+20; no concentración actual | https://kamino.com/docs/kmno

## Desbloqueos
- Fecha próxima de desbloqueo = October 30, 2026 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- KMNO del próximo evento = 229,166,667 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- KMNO bloqueados declarados por proveedor = 4,224,999,998 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Porcentaje bloqueado declarado por proveedor = 42.2% | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- KMNO restantes en eventos futuros declarados = 1,375,000,002 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Porcentaje de eventos futuros declarado = 13.8% | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Circulante actual declarado por proveedor KMNO = 1,000,000,000 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Próximas fechas visibles = Nov 30, 2026; Dec 30, 2026; Jan 30, 2027 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Fecha final declarada por proveedor = March 30, 2027 | consulta=2026-10-28T19:00:30Z; NO validar porcentaje bloqueado ni calendario completo por contradicciones internas | https://app.tokenomics.com/tokenomics/kamino/unlocks
- KMNO del próximo evento redondeados = 229.17M | sección=Upcoming KMNO Unlock; datos atribuidos a Tokenomist, no corroboración independiente entre ambos | https://www.coingecko.com/en/coins/kamino
- KMNO a stakeholders y asesores redondeados = 145.83M | sección=Upcoming KMNO Unlock; datos atribuidos a Tokenomist, no corroboración independiente entre ambos | https://www.coingecko.com/en/coins/kamino
- KMNO a contribuidores redondeados = 83.33M | sección=Upcoming KMNO Unlock; datos atribuidos a Tokenomist, no corroboración independiente entre ambos | https://www.coingecko.com/en/coins/kamino
- Porcentaje efectivamente bloqueado = no verificado | contradicción entre cantidades futuras y bloqueadas; no usar complemento del circulante | https://app.tokenomics.com/tokenomics/kamino/unlocks
- Desbloqueo sobre oferta planificada % = 2.29166667 | calculado=229166667/10000000000*100 | https://app.tokenomics.com/tokenomics/kamino/unlocks ; https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Desbloqueo sobre circulante de referencia % = 3.9082269921874127 | calculado=229166667/5863698998.5*100 | https://app.tokenomics.com/tokenomics/kamino/unlocks ; https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false
- Valor nocional USD del desbloqueo = 8887775.42959434 | calculado=229166667*0.03878302; no ejecución | https://app.tokenomics.com/tokenomics/kamino/unlocks ; https://api.coingecko.com/api/v3/coins/kamino?localization=false&tickers=false&market_data=true&community_data=false&developer_data=false&sparkline=false

## TVL, préstamos y actividad económica
- TVL agregado USD = 1334322110 | https://api.llama.fi/protocol/kamino
- Préstamos activos agregado USD = 861676808 | https://api.llama.fi/protocol/kamino
- Timestamp Unix último TVL agregado = 1793210591 | https://api.llama.fi/protocol/kamino
- Timestamp UTC último TVL agregado = 2026-10-28T18:03:11+00:00 | https://api.llama.fi/protocol/kamino
- Consulta HTTP = 2026-10-28T18:59:48.888173+00:00 | https://api.llama.fi/protocol/kamino
- TVL Lend USD = 1262710903.98576 | componente del agregado; no sumar ambos TVL | https://api.llama.fi/protocol/kamino-lend
- Préstamos activos Lend USD = 861676808.55988 | componente del agregado; no sumar ambos TVL | https://api.llama.fi/protocol/kamino-lend
- Timestamp UTC último TVL Lend = 2026-10-28T17:48:59+00:00 | componente del agregado; no sumar ambos TVL | https://api.llama.fi/protocol/kamino-lend
- Comisiones agregado 30 días USD = 4.82m | consulta=2026-10-28T19:00:18Z; cifras tal como aparecen en página | https://defillama.com/protocol/kamino
- Ingresos agregado 30 días USD = 623,535 | consulta=2026-10-28T19:00:18Z; cifras tal como aparecen en página | https://defillama.com/protocol/kamino
- Ingresos agregado 24 horas USD = 19,138 | consulta=2026-10-28T19:00:18Z; cifras tal como aparecen en página | https://defillama.com/protocol/kamino
- Ingresos acumulados agregado USD = 51.25m | consulta=2026-10-28T19:00:18Z; cifras tal como aparecen en página | https://defillama.com/protocol/kamino
- Ingresos a holders agregado 30 días USD = 0 | consulta=2026-10-28T19:00:18Z; cifras tal como aparecen en página | https://defillama.com/protocol/kamino
- Ingresos Lend 30 días USD = 604,908 | consulta=2026-10-28T19:00:18Z; componente del agregado | https://defillama.com/protocol/kamino-lend
- Usuarios o direcciones activas actuales = no verificado | sin serie actual con definición y ventana comparables | https://defillama.com/protocol/kamino-lend

## Muestra DEX por mint exacto
- Consulta HTTP DEX = 2026-10-28T18:59:45.145761+00:00 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Pares únicos devueltos = 30 | calculado=filtrar mint y deduplicar pairAddress; no censo universal | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Suma liquidez muestra USD = 2453366.89 | calculado=sum(liquidity.usd); no profundidad de ejecución | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Suma volumen 24 h muestra USD = 3285949.45 | calculado=sum(volume.h24); no volumen global del token | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez del pool principal sobre muestra % = 80.33883305566252 | calculado=1971006.33/suma_liquidez*100 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/USDC pool=3ndjN1nJVUKGrJBc1hhVpER6kWTZKHdyDrPyCJyX3CXK = 1971006.33 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/USDC pool=3ndjN1nJVUKGrJBc1hhVpER6kWTZKHdyDrPyCJyX3CXK = 3090399.1 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/JitoSOL pool=2nJjE2ba3iGtefN4UNM1KN5FdYCwssU4Bzhc8URceqh6 = 268646.49 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/JitoSOL pool=2nJjE2ba3iGtefN4UNM1KN5FdYCwssU4Bzhc8URceqh6 = 131649.39 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/SOL pool=5LziHU8Z1iKadAmPFWQi2Rn2MvTvXYKVFt1ZDevbvKFx = 47130.42 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/SOL pool=5LziHU8Z1iKadAmPFWQi2Rn2MvTvXYKVFt1ZDevbvKFx = 3786.97 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=5E2cHo3DQnRjB3zWHKUs86RPqCeLboMgKV9WjxFwUjhV = 46765 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=5E2cHo3DQnRjB3zWHKUs86RPqCeLboMgKV9WjxFwUjhV = 36360.81 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/SOL pool=4UopaeYzxPyHtSYcvb1Cj9U3Z8uUf3yngsrTExqi2JAh = 44426.37 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/SOL pool=4UopaeYzxPyHtSYcvb1Cj9U3Z8uUf3yngsrTExqi2JAh = 5924.47 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD raydium KMNO/SOL pool=6tpEjdVoV7spGbE4RdXNxmRXbw4wb5ouLupDWpLYZyNH = 38935.08 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD raydium KMNO/SOL pool=6tpEjdVoV7spGbE4RdXNxmRXbw4wb5ouLupDWpLYZyNH = 5057.66 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/PYUSD pool=JDELdNKDVFQqAodu79QcgnYbZJA8H3HXKxLQ7MzxByZb = 9627.73 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/PYUSD pool=JDELdNKDVFQqAodu79QcgnYbZJA8H3HXKxLQ7MzxByZb = 3.53 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/USDC pool=8Cn9qjjhyzA5GxtbD2HUkuDio6CmpXRV7vFUAYDtyP1X = 5489.47 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/USDC pool=8Cn9qjjhyzA5GxtbD2HUkuDio6CmpXRV7vFUAYDtyP1X = 220.39 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=HRMCMdMfo1VPP4PCL6jRndEEYCUmRGVsZVkgCHD8eo6U = 4240.1 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=HRMCMdMfo1VPP4PCL6jRndEEYCUmRGVsZVkgCHD8eo6U = 1480.41 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/SOL pool=C6CPvrwyhsN5MR5931r4cuoNhnsfV3mVqQT9as1vNcRX = 3814.7 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/SOL pool=C6CPvrwyhsN5MR5931r4cuoNhnsfV3mVqQT9as1vNcRX = 2811.6 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/USDC pool=4VGetbiGroMGmFsqedF6t6PyYXXk9mzwxV8b7BSb3s9T = 2939.88 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/USDC pool=4VGetbiGroMGmFsqedF6t6PyYXXk9mzwxV8b7BSb3s9T = 0.85 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=3JAM9qgRCcAmECiXGekojjBgkZfTQFi9eRUtUf5GyH5f = 2295.74 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=3JAM9qgRCcAmECiXGekojjBgkZfTQFi9eRUtUf5GyH5f = 110.83 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/USDC pool=osVXiSe9kmZ8VvBsesUVbTwAg6M84Se6A4xFFuHkpif = 1805.28 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/USDC pool=osVXiSe9kmZ8VvBsesUVbTwAg6M84Se6A4xFFuHkpif = 7503.81 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/SOL pool=DqwDrSibfaPq7gL52VdcMAjzQY7vkc9tTz4KrUumHsNw = 1233.08 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/SOL pool=DqwDrSibfaPq7gL52VdcMAjzQY7vkc9tTz4KrUumHsNw = 98.22 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/cbBTC pool=3vPuf4JgMxHFnUYQAbeaUhmGo9v5TjxMs2LLr2bECwE6 = 1068.03 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/cbBTC pool=3vPuf4JgMxHFnUYQAbeaUhmGo9v5TjxMs2LLr2bECwE6 = 14.64 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/A pool=7b5sGg5LRwKDt2U32MxZxAqKwkGpid48egQFyqiTJsNb = 731.8 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/A pool=7b5sGg5LRwKDt2U32MxZxAqKwkGpid48egQFyqiTJsNb = 10.23 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/JitoSOL pool=AkybmedkWE9Srsy1sYKTaih5dza3zvqYCdqthsEYELLD = 706.93 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/JitoSOL pool=AkybmedkWE9Srsy1sYKTaih5dza3zvqYCdqthsEYELLD = 23.27 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/CARDS pool=JB3W4d6tQHXNsXzpGHE92MNkJzaKaTGRQ1zaMHSWwrpD = 623.86 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/CARDS pool=JB3W4d6tQHXNsXzpGHE92MNkJzaKaTGRQ1zaMHSWwrpD = 315.71 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=EwjCEwdri8DyiMD3QbsKRawko5SGXwfKUDTpDVwfP7NX = 367.37 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=EwjCEwdri8DyiMD3QbsKRawko5SGXwfKUDTpDVwfP7NX = 151.2 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/TYTR pool=Fhg6hCCJQuWw8BW6THWVveP2rGueQpLkEVVfbAywPWm4 = 256.07 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/TYTR pool=Fhg6hCCJQuWw8BW6THWVveP2rGueQpLkEVVfbAywPWm4 = 1.15 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD raydium KMNO/USDC pool=Cqyw69CjGBtwqewM4ETbbzqQ4wui8QT48VFg91dDNQe8 = 254.61 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD raydium KMNO/USDC pool=Cqyw69CjGBtwqewM4ETbbzqQ4wui8QT48VFg91dDNQe8 = 0 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/ARBX pool=2aHNxVCE3mNUQXsCiaZ3MqUVuCZ4Mvf26NqZAHoX2t7P = 197.93 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/ARBX pool=2aHNxVCE3mNUQXsCiaZ3MqUVuCZ4Mvf26NqZAHoX2t7P = 5.21 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/ASTY pool=2Gk1FWW4vKJ23pR42WnAfg7RG4UtMfEpKUKTsYMNCfax = 185.76 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/ASTY pool=2Gk1FWW4vKJ23pR42WnAfg7RG4UtMfEpKUKTsYMNCfax = 1.42 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/Pawel pool=4ST8AFEKGndbhXb5yEfrx341aF96PAc2GRxiWRpsb8e2 = 177.21 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/Pawel pool=4ST8AFEKGndbhXb5yEfrx341aF96PAc2GRxiWRpsb8e2 = 3.53 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/SOL pool=G1KhmXd1erek8ghGEoFvnjp6VJqsb1BiQeeRT2oAvryd = 173.47 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/SOL pool=G1KhmXd1erek8ghGEoFvnjp6VJqsb1BiQeeRT2oAvryd = 7.98 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD raydium KMNO/SOL pool=tgFZrEjTnywXageMuvXNJEWYWs8o4XjtmAXY75HNLm2 = 104.68 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD raydium KMNO/SOL pool=tgFZrEjTnywXageMuvXNJEWYWs8o4XjtmAXY75HNLm2 = 0.92 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=7t6yo3ii96aEqm11iHsZpG6M4aiX397DYP9BFeizfa7a = 82.13 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=7t6yo3ii96aEqm11iHsZpG6M4aiX397DYP9BFeizfa7a = 2.54 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD meteora KMNO/USDC pool=71bCxoBabxHXDcqEXtcmR7FwrYUGe7UbfZAbpfFPNu65 = 69.11 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD meteora KMNO/USDC pool=71bCxoBabxHXDcqEXtcmR7FwrYUGe7UbfZAbpfFPNu65 = 2.3 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD raydium KMNO/SOL pool=9FvyHZb352FauJCFvbgLgbPaarCnhSjPKUABa76QttfW = 8.93 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD raydium KMNO/SOL pool=9FvyHZb352FauJCFvbgLgbPaarCnhSjPKUABa76QttfW = 0.94 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Liquidez USD orca KMNO/SOL pool=8dbPoWiHJWDcvg24ZCmWn6b4KjEBwb1ycMqQNRvANj6q = 3.33 | campo=liquidity.usd | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Volumen 24 h USD orca KMNO/SOL pool=8dbPoWiHJWDcvg24ZCmWn6b4KjEBwb1ycMqQNRvANj6q = 0.37 | campo=volume.h24 | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Precio USD pool KMNO/USDC Orca = 0.03881 | campo=priceUsd; no promedio con precio agregado | https://api.dexscreener.com/token-pairs/v1/solana/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- CEX spot observados = Binance; OKX; Bybit | tabla=Kamino Markets; no implica disponibilidad para tu jurisdicción | https://www.coingecko.com/en/coins/kamino

## RaptorX y bounty
- Estado de presencia operativa de KMNO en RaptorX = en captura; no verificado | sin reporte generado verificado en este paquete | https://raptorx.trade/solana/KMNO
- Timestamp de captura local previa = 2026-10-28T17:53:47Z | archivo=kmno_captura_1.json; usar timestamp del archivo, no horario referido en mensajes anteriores | https://raptorx.trade/solana/KMNO
- Respuesta de ruta directa = We couldn't load this token from the URL. | evidencia local previa, no prueba de ausencia global | https://raptorx.trade/solana/KMNO
- Bolsa total = 125 USDC | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Primer lugar = 75 USDC | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Segundo lugar = 50 USDC | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Cierre UTC = 2026-11-02T03:59:59.000Z | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Estado = OPEN | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Acceso agentes = AGENT_ALLOWED | consulta=2026-10-28T18:59:46.774756+00:00 | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha
- Requisito de evidencia = reporte generado dentro de RaptorX más pregunta pertinente y capturas legibles | este informe externo no reemplaza la interacción exigida | https://superteam.fun/api/listings/details/raptorx-research-challenge-ask-better-questions-find-better-alpha

## Accesos incompletos y control de procedencia
- Birdeye = no verificado; extracción fallida y curl HTTP 403 | sin usar claves ni datos de cuenta | https://birdeye.so/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS?chain=solana
- Tokenomist, detalle de eventos = no verificado; extracción informó login o paywall | CoinGecko atribuye sus desbloqueos a Tokenomist | https://tokenomist.ai/kamino/unlock-events
- Solscan por navegador = verificación de seguridad; holders no recuperados | no se resolvió el desafío ni se autenticó | https://solscan.io/token/KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS
- Riesgos de vaults = contratos; crédito; curadores; liquidez de retiro | documentación oficial; sin asignar probabilidades inventadas | https://kamino.com/docs/products/lending-vaults/risks.md
- Riesgos de apalancamiento = pérdidas amplificadas; tasa variable; liquidación según estrategia | documentación oficial; no extrapolar una estrategia a todas | https://kamino.com/docs/products/multiply/risks.md

Respuestas completas, errores HTTP, textos extraídos y cálculos: `evidencia-KMNO-1/`. El archivo `fetch-index.json` identifica URL, momento de descarga y estado HTTP. `calculations.json` separa cálculos de capturas. Los archivos `*-pretty.json` son representaciones legibles de respuestas JSON o proyecciones de sus campos, no nuevos datos.
