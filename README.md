# Datos del bot de fundamentales (EDGAR, 2009–2025)

Datos **derivados de los balances públicos de la SEC** (EDGAR XBRL `companyfacts`), con la fecha real de presentación de cada balance, para un estudio académico pre-registrado (sello en OpenTimestamps). Los lee un notebook de QuantConnect. No contienen precios ni resultados de ninguna estrategia.

| Archivo | Contenido |
|---|---|
| `capa2_edgar.txt` | Por fecha de rebalanceo y empresa del S&P 500 (no financiera): puntaje F de Piotroski, filtros de caja y deuda, CIK e insumos de valuación |
| `chs_edgar.txt` | Insumos contables del modelo de Campbell, Hilscher y Szilagyi (2008) |
| `ciks_fja.txt` | CIK de la SEC de cada tramo de pertenencia al S&P 500 |
| `indice.txt` | SHA-256 y cantidad de líneas de cada archivo |

Fuente de los datos: U.S. Securities and Exchange Commission (información pública). La lista de miembros del S&P 500 proviene de fja05680/sp500.
