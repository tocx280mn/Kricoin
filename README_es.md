# Resumen de configuraci\u00f3n de Kricoin

A continuaci\u00f3n se detallan los par\u00e1metros principales de la criptomoneda **Kricoin**.

| Secci\u00f3n | Par\u00e1metro | Valor actual | Descripci\u00f3n |
| --- | --- | --- | --- |
| **Identidad** | nombre de la moneda | Kricoin | Nombre personalizado de tu moneda |
| | código de moneda | KRC | Abreviatura est\u00e1ndar |
| | byte identificador de dirección | 0x2D | Direcciones comienzan con K |
| | byte identificador para multisig | 0x30 | Para direcciones multifirma (K tambi\u00e9n) |
| **Minado** | algoritmo de hash | scrypt | Algoritmo de miner\u00eda elegido |
| | dificultad inicial | 0.000050 | Muy baja, para facilitar inicio |
| | segundos deseados entre bloques | 60 | Bloques cada 1 minuto |
| | segundos para cambio de dificultad | 216000 | Ajuste cada 2.5 d\u00edas |
| **Recompensas** | recompensa inicial por bloque | 100 | Recompensa por bloque inicial |
| | bloques hasta reducir recompensa a la mitad | 1680000 | Halving muy espaciado (~8 a\u00f1os) |
| **Comisiones** | mínimo enviable sin comisión dust | 0.00100000 (predeterminado) | A\u00fan requiere fee para evitar spam |
| | mínimo enviable total | 0.00010000 (predeterminado) | L\u00edmite inferior para micropagos |
| | transacción más grande sin comisión por tamaño | 10000 (predeterminado) | Tama\u00f1o sin fee por exceso de bytes |
| **Bloques** | límite de tamaño de bloque | 1000000 (predeterminado) | 1 MB como en Bitcoin (ajustable si crece la red) |
| **Génesis** | mensaje de génesis | Personalizado por ti | Frase simb\u00f3lica fundacional (s\u00f3lo ASCII) |
| **Governance** | gobernanza | 000...000 (predeterminado vacío) | Sin sistema de gobernanza activo |

