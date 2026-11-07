# Cambios

## 0.9.6 · GP-50 Custom Firmware v14 + app Android

### Firmware v14 (Valeton GP-50, base oficial V1.1.0)

- **FX Carousel en la vista de cadena (PARA):**
  - ilustraciones animadas para cada bloque: NR, PRE, DST, AMP, CAB, EQ, MOD, DLY, RVB, N→S y EXP;
  - carrusel al girar PARA, con brillo del color del efecto y mapa de la cadena;
  - carga del DSP en la cabecera;
  - el panel de parámetros de abajo se oscurece para encajar con el carrusel.
- **Global Settings con el estilo del diseño elegido:**
  - Studio: tarjetas;
  - Vintage Amp: tolex, placas crema y display ámbar;
  - Neon: synthwave;
  - Pro: lista.
  - En Appearance, Global EQ y Layouts, cada ajuste aparece junto a su control: P, L, M o R.
- **Cuándo se activa:** con cualquier diseño distinto de Original. Con Original, todo es como en la v13.1.

### GP50 Custom Studio para Android 0.9.6 (nuevo)

- **Qué es:** el editor en el móvil, conectado a la GP-50 por **Bluetooth LE**.
- **Conexión:**
  - la app habla con la característica BLE-MIDI de la pedalera directamente, con un paquete por mensaje, tal como lo exige su firmware;
  - las respuestas por Bluetooth, que llegan en tramas de 100 bytes, se convierten a las tramas de 19 bytes de USB;
  - solo muestra «conectada» cuando la pedalera ya ha respondido.
- **Interfaz para el móvil:**
  - tarjeta de conexión compacta;
  - barra fija para cambiar de preset;
  - cadena de pedales que cabe en la pantalla;
  - 4 mandos por fila;
  - pestañas Presets, Editor, Firmware y Más.
- **Diagnóstico Bluetooth:** se puede copiar o compartir.
- **Requisitos:** Android 8 o superior con Bluetooth LE.

### Editor de escritorio

- Sigue siendo la 0.9.5, ya compatible con el firmware v14 (release v0.9.5).
## 0.9.5 · editor + GP-50 Custom Firmware v13.1

### Firmware v13.1 (Valeton GP-50, base oficial V1.1.0)
- **Animación de carga guardada:** la elegida se mantiene al apagar con el USB conectado (en v13 siempre salía Classic).
- **7 animaciones de carga (v13):** Classic, Liquid, Ring, VU, Synth, Logo y Spectrum, con «Custom FW by Dokken», nivel real de la batería y FULL al terminar. Knob R en la casilla Layouts.
- **5 diseños de la pantalla principal (v12–v12.1):** Original, Studio, Vintage Amp, Neon y Pro. Nueva casilla **Layouts** en la 4.ª página de Global Settings (pulsar PARA).
- **BYE BYE al apagar (v11.2):** animación de despedida.
- **EQ global más robusta (v11.2):** sin chasquidos ocasionales con la EQ activada.
- Arranque seguro (A + B al encender): también vuelve al diseño Original y a la animación de carga Classic.
- Incluye todo lo anterior: NAM + CAB a la vez, VOL del CAB hasta +12 dB, EQ global, colas de delay y reverb, medidor de DSP, 12 temas, 15 modos de LED, 3 animaciones de arranque, atenuación automática y enlace con el editor.

### Editor 0.9.5
- Detección fiable del firmware v12/v13: el editor reensambla las respuestas que la pedalera envía en varias tramas (0.9.5).
- Sección **Animación de carga** con vista previa animada (0.9.4).
- Sección **Diseño de la pantalla principal** con vistas previas generadas con el mismo modelo que el pedal (0.9.3).

## 0.9.2 · editor + GP-50 Custom Firmware v11.1

### Firmware v11.1 (Valeton GP-50, base oficial V1.1.0)
- **Global EQ en el pedal:** nueva casilla en una cuarta página de Global Settings. PARA o knob L cambian el perfil y el knob R activa o desactiva las colas.
- **Appearance más legible:** 4 líneas, cada una con su control (`[P]` `[L]` `[M]` `[R]`).
- **EQ global (v11):** 4 bandas al final de la cadena (graves 120 Hz, medios 650 Hz, agudos 2,2 kHz, presencia 4,5 kHz). Off, Custom (±12 dB en pasos de 2 dB) y 15 perfiles: Rock, Hard Rock, Classic Rock, Clean, Blues, Jazz, Funk, Country, Heavy Metal, Metalcore, Djent, Doom/Stoner, Ambient, Live/FRFR y Headphones.
- **Colas de delay y reverb (v11):** si el preset nuevo usa el mismo modelo de DLY o RVB, la cola sigue sonando.
- **Medidor de DSP (v10–v11):** recuadro propio junto al nombre del preset, con colores según la carga.
- Arranque seguro (A + B al encender): también desactiva la EQ y las colas.
- Incluye todo lo anterior: NAM + CAB a la vez, VOL del CAB hasta +12 dB, 12 temas, 15 modos de LED, 3 animaciones de arranque, atenuación automática y enlace con el editor.

### Editor 0.9.2
- Panel del firmware: sección **EQ global** con la curva real de cada perfil y editor Custom.
- Sección **Colas de delay y reverb**.
- Carga del DSP en vivo y opción de ocultar el medidor del pedal (0.9.1).
- Panel del firmware con temas, LEDs, animación de arranque y atenuación (0.9.0).

## 0.8.1
- Primera versión publicada del editor (Windows 11 x64).

