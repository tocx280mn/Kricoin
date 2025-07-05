Kricoin 0.8.x BETA
====================

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers

Distribuido bajo la licencia de software MIT/X11; consulte el archivo COPYING o http://www.opensource.org/licenses/mit-license.php.
Este producto incluye software desarrollado por el Proyecto OpenSSL para su uso en el OpenSSL Toolkit.
Este producto incluye software criptográfico escrito por Eric Young (eay@cryptsoft.com), y software UPnP escrito por Thomas Bernard.


Introducción
---------------------
Kricoin es un sistema de dinero electrónico peer-to-peer de código abierto y gratuito que está completamente descentralizado, sin necesidad de un servidor central ni de partes de confianza.
Los usuarios poseen las claves criptográficas de su propio dinero y realizan transacciones directamente entre sí, con la ayuda de una red P2P para comprobar el doble gasto.


Configuración
---------------------
Necesita las bibliotecas en tiempo de ejecución de Qt4 para ejecutar Kricoin-Qt. En Debian o Ubuntu:
        `sudo apt-get install libqtgui4`

Descomprima los archivos en un directorio y ejecute:

- bin/32/kricoin-qt (GUI, 32-bit)
- bin/32/kricoind (sin interfaz, 32-bit)
- bin/64/kricoin-qt (GUI, 64-bit)
- bin/64/kricoind (sin interfaz, 64-bit)

Consulte la documentación en el [Wiki de Kricoin](http://kricoin.info) para obtener ayuda y más información.


Otras páginas
---------------------
- [Notas de compilación para Unix](build-unix.md)
- [Notas de compilación para OSX](build-osx.md)
- [Notas de compilación para Windows](build-msw.md)
- [Guías de estilo de código](coding.md)
- [Proceso de lanzamiento](release-process.md)
- [Notas de lanzamiento](release-notes.md)
- [Desarrollo de Multiwallet Qt](multiwallet-qt.md)
- [Pruebas unitarias](unit-tests.md)
- [Proceso de traducción](translation_process.md)
