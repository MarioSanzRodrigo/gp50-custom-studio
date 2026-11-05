# Privacidad

La web de presentación no incorpora formularios, cuentas, publicidad ni analítica propia. Sus demostraciones no solicitan acceso MIDI/audio. Cloudflare y GitHub pueden procesar los datos técnicos de conexión conforme a sus políticas.

La aplicación de escritorio V2 funciona localmente con Electron y un perfil separado de Edge. En su carpeta de datos guarda ajustes, caché de presets, backups, descargas NAM y un registro limitado de operaciones/errores. No distribuye esos datos con el instalador ni los envía automáticamente al desarrollador.

MIDI se usa para comunicarse con la GP-50. El audio se activa por separado y se analiza localmente para afinación, nivel USB y comparación RMS; el editor no lo graba ni lo sube a Internet.

TONE3000 se carga desde su sitio oficial en una vista aislada, sin acceso a Node, al preload del editor ni a sus permisos MIDI/audio. El login y las cookies se guardan en una partición propia del perfil V2. Al iniciar sesión, navegar o descargar se aplican las políticas de TONE3000 y de sus proveedores. El editor no incluye claves ni sesiones del desarrollador.

Los informes de diagnóstico solo se guardan/exportan por iniciativa del usuario. Antes de compartir un archivo en el foro o GitHub revisa sus datos. La desinstalación conserva backups y datos locales del usuario.
