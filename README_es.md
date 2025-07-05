# Resumen de configuraci\u00f3n de Kricoin

A continuaci\u00f3n se detallan los par\u00e1metros principales de la criptomoneda **Kricoin**.

| Secci\u00f3n | Par\u00e1metro | Valor actual | Descripci\u00f3n |
| --- | --- | --- | --- |
| **Identidad** | coin name | Kricoin | Nombre personalizado de tu coin |
| | currency code | KRC | Abreviatura est\u00e1ndar |
| | address identifier byte | 0x2D | Direcciones comienzan con K |
| | multisig address identifier byte | 0x30 | Para direcciones multifirma (K tambi\u00e9n) |
| **Minado** | hash algorithm | scrypt | Algoritmo de miner\u00eda elegido |
| | starting difficulty | 0.000050 | Muy baja, para facilitar inicio |
| | desired seconds between blocks | 60 | Bloques cada 1 minuto |
| | desired seconds to difficulty change | 216000 | Ajuste cada 2.5 d\u00edas |
| **Recompensas** | initial block reward | 100 | Recompensa por bloque inicial |
| | blocks until reward halves | 1680000 | Halving muy espaciado (~8 a\u00f1os) |
| **Comisiones** | minimum sendable without dust fee | 0.00100000 (default) | A\u00fan requiere fee para evitar spam |
| | minimum sendable at all | 0.00010000 (default) | L\u00edmite inferior para micropagos |
| | largest tx in bytes without size fee | 10000 (default) | Tama\u00f1o sin fee por exceso de bytes |
| **Bloques** | block size limit | 1000000 (default) | 1 MB como en Bitcoin (ajustable si crece la red) |
| **Genesis** | genesis message | Personalizado por ti | Frase simb\u00f3lica fundacional (s\u00f3lo ASCII) |
| **Governance** | governance | 000...000 (default vac\u00edo) | Sin sistema de gobernanza activo |

