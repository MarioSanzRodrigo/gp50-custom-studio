# Cambios

## 0.7.0-beta.1 — 4 de noviembre de 2026

Beta unificada: incorpora el afinador visual, control MIDI CC58, nivel USB de pico/RMS y comparación asistida de presets por RMS. Instrumentos compactos integrados en el editor. Selección automática del canal con señal y activación de audio explícita. El indicador de afinación tiene el doble de altura y la nota centrada.

Las lecturas MIDI completas ya no esperan 400 ms de silencio; se conservan las pausas de seguridad y la parada ante errores. No se ofrece un porcentaje DSP sin medición real.


## 0.6.1-beta.1 — 4 de noviembre de 2026

Primera beta pública empaquetada del editor base.

- Interfaz española con parámetros en inglés, cadena visual y valores numéricos editables.
- Nombre editable en la cabecera y controles Volume/BPM accesibles.
- Navegación mediante flechas anterior/siguiente.
- Corrección de posición de presets: el ID interno no se interpreta como número de slot.
- Invalidación de nombres antiguos tras escribir y renovación de caché.
- Paquete Windows portable, fuentes del conversor, licencias y sumas SHA256.

La Pro se desarrolla por separado. El afinador y los medidores USB no forman
parte de esta beta base. No se presenta un porcentaje de DSP estimado como real.
