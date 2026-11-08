# GP-50 Custom Firmware by Dokken · GP50 Custom Studio

Firmware custom, editor de escritorio y app Android para **Valeton GP-50**, por [Dokken](https://guitarristas.info/usuarios/dokken7789).

**[Web, wiki y descargas](https://gp50-custom-studio.pages.dev/)** · [Release v0.9.7](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/tag/v0.9.7)

| | Versión | Descarga |
|---|---|---|
| GP-50 Custom Firmware | v14 (base oficial V1.1.0) | [GP-50_V1.1.0_NAMCAB_v14_FXStyles.bin](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.9.7/GP-50_V1.1.0_NAMCAB_v14_FXStyles.bin) |
| GP50 Custom Studio para Android | 0.9.7 · Android 8+ · Bluetooth | [APK](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.9.7/GP50-Custom-Studio-0.9.7-Android.apk) · [Fuentes](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.9.7/GP50-Custom-Studio-0.9.7-Sources.zip) |
| GP50 Custom Studio Editor | 0.9.6 · Windows 11 x64 | [Instalador](https://github.com/MarioSanzRodrigo/gp50-custom-studio/releases/download/v0.9.7/GP50-Custom-Studio-0.9.6-Setup.exe) |

## Firmware

- **FX Carousel (v14):** al pulsar PARA, la vista de cadena muestra ilustraciones animadas de cada efecto en carrusel, con la carga del DSP en la cabecera.
- **Global Settings con estilo (v14):** tarjetas, vintage, neon o lista, según el diseño elegido.
- **NAM + CAB a la vez**, con VOL del CAB hasta +12 dB.
- **EQ global** de 4 bandas para todos los presets: Off, Custom y 15 perfiles por estilo.
- **Colas** de delay y reverb entre presets.
- **Medidor de carga del DSP** junto al nombre del preset.
- **5 diseños** de la pantalla principal: Original, Studio, Vintage Amp, Neon y Pro.
- **7 animaciones de carga** con la pedalera apagada y el USB conectado, y **BYE BYE** al apagar.
- **12 temas** de pantalla, **15 modos** de LED, **3 animaciones** de arranque y **atenuación** automática.
- **Compatibilidad hacia atrás:** cada versión del firmware conserva todo lo anterior; el editor y la app activan cada función según la versión mínima que la introdujo.
- **Seguridad:** arranque seguro con A + B al encender, y vuelta al firmware oficial con el actualizador de Valeton.

Instrucciones y notas en `FIRMWARE-v14.md`, dentro de la release. Guías con capturas en la [wiki](https://gp50-custom-studio.pages.dev/wiki.html).

## App Android

Es el mismo editor en el móvil y se conecta a la GP-50 por **Bluetooth**, sin cables.

- **Funciones:**
  - presets y cadena visual;
  - edición en vivo;
  - copias;
  - el panel completo del firmware custom.
- **Interfaz para el móvil:**
  - pestañas Presets, Editor, Firmware y Más;
  - barra fija para cambiar de preset;
  - 4 mandos por fila.

Para instalarla, descarga el APK en el móvil y permite «Instalar apps desconocidas». Cierra Valeton Suite antes de conectar: la pedalera solo acepta una conexión Bluetooth de datos a la vez.

## Editor de escritorio

- **Funciones:**
  - presets y cadena visual;
  - afinador y nivel USB;
  - NAMs e IRs;
  - copias con SHA-256;
  - TONE3000 integrado.
- **Panel del firmware custom:**
  - temas, diseños de pantalla y animaciones de carga;
  - LEDs, arranque y atenuación;
  - carga del DSP;
  - EQ global y colas.

Cierra Valeton Suite y otros editores antes de conectar. El instalador no lleva firma digital comercial.

## Repositorio

- **Documentación:** este repositorio solo la contiene.
- **Código:** el código completo va en `Sources.zip`, dentro de cada release. Incluye el editor y, desde la 0.9.6, la app Android. El «Source code» automático de GitHub solo contiene este árbol de documentación.
- **Licencias:**
  - el editor y la app están bajo GPL-3.0-only, con componentes MIT y los avisos de Electron/Chromium conservados;
  - el firmware es una modificación del firmware oficial de Valeton, cuyos derechos pertenecen a Valeton.

Proyecto independiente, sin vinculación oficial con Valeton. Sin garantía: lo instalas bajo tu responsabilidad.
