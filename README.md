# GP50 Custom Studio Editor · 0.8.1

Editor independiente para Valeton GP-50, por Mario S.R. - Dokken. Aplicación de escritorio para Windows 11 x64, con Electron integrado, afinador, niveles USB y nuestra cadena de efectos visual.

[Web y descarga](https://gp50-custom-studio.pages.dev/) · [Instalador Windows](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.8.1/GP50-Custom-Studio-0.8.1-Setup.exe) · [Fuentes completos](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.8.1/GP50-Custom-Studio-0.8.1-Sources.zip)

NAMs e IRs muestra los presets asociados y su estado activo/bypass, con cobertura de lectura explícita y análisis cancelable. Se elimina la creación de presets desde NAM y la etiqueta V2 preview de la interfaz.

La biblioteca guarda presets y backups independientes de archivos SnapTone/IR, con SHA256, importación/exportación y recuperación de archivos individuales. Estos últimos contienen archivos disponibles localmente: no son un volcado binario de los modelos/IR de la GP-50. Para slots cargados con otros programas, aporta sus originales; la aplicación muestra los que siguen sin archivo recuperable.

Cierra Suite y otros editores antes de instalar/conectar. El instalador conserva el perfil anterior. Firmware de referencia: GP-50 1.1.0. Instalador sin firma digital comercial. Las pruebas automáticas no equivalen a comprobaciones físicas de todas las operaciones.

Este repositorio contiene documentación. El código completo está en el Sources.zip adjunto a la release; el Source code automático de GitHub solo contiene el árbol de documentación de su tag. Los fuentes incluyen instrucciones de construcción y tests. GPL-3.0-only, con componentes MIT y avisos Electron/Chromium conservados. Proyecto independiente, sin vinculación oficial con Valeton.