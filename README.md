# GP50 Custom Studio Editor

Editor independiente y portable para Valeton GP-50 en Windows 11.
Desarrollado por Mario S.R. — [Dokken](https://www.guitarristas.info/usuarios/dokken7789).

**Beta pública 0.6.1-beta.1.** Probada en el equipo del desarrollador con firmware
1.1.0; la compatibilidad en otros equipos necesita más pruebas. No es un producto
oficial de Valeton. La versión Pro experimental no se incluye en esta descarga.

## Uso

Descarga el ZIP Windows desde Releases, extrae toda la carpeta, cierra otros
editores, conecta la GP-50 y abre `Abrir editor.cmd`. Pulsa Reconectar MIDI o
Actualizar lista rápida y acepta el permiso del navegador. Utiliza Microsoft Edge.
No instales Node ni Python para usar la versión portable.

Selecciona un preset para escucharlo y editarlo. Los cambios de parámetros se
guardan en la pedalera al soltar el control. Haz antes una copia de tus presets.
Para detener el servidor local ejecuta `Cerrar editor.cmd`.

## Funciones

- Selección de presets y navegación anterior/siguiente.
- Cadena visual, parámetros con perillas y entrada numérica.
- Guardar copia, restaurar la base de la sesión y exportar .prst.
- Gestión de capturas e IRs; conversión local NAM A1/A2 compatible a SnapTone.
- Comunicación MIDI serializada; ante un error se detiene sin reintentos automáticos.

NAM requiere un WAV de referencia de la instalación local de Valeton Suite o un
archivo suministrado por el usuario. **Ese audio no se distribuye**. Suite no tiene
que estar abierta. TONE3000 abre el sitio oficial para iniciar sesión y descargar;
el archivo descargado se selecciona después en el editor. No se anuncia selección
automática desde la web ni soporte para todas las arquitecturas NAM.

## Desarrollo y fuentes

Descarga y extrae el archivo Sources.zip de la release para obtener el árbol de desarrollo. Dentro de ese archivo, `studio/` contiene el editor completo distribuido, incluidas las fuentes del worker,
TypeScript y C del conversor en `studio/converter/`. `overrides/` contiene las
adaptaciones del editor base. `reference/valeton-gp50-master/app/static/` es la base
MIT necesaria para regenerar. En PowerShell ejecuta `./build.ps1` y después
`./Build-Portable.ps1`. Ninguno necesita acceder a la pedalera para construir.

El motor puede regenerarse con Node24+ mediante `node converter/build.mjs` y,
con clang con soporte wasm32/SIMD, `node converter/build-wasm.mjs`. Consulta su
README y NOTICE. Los kernels precompilados están incluidos.

Para ejecutar las comprobaciones sin hardware:

```powershell
node -e "(async()=>{for(const t of ['midi-safety','auto-edit','snaptone-codec','tone3000'])console.log(t,await require('./tests/'+t+'.cjs')())})().catch(e=>{console.error(e);process.exit(1)})"
```

Publica incidencias con el firmware, versión del editor, navegador y mensaje de
error. No adjuntes contraseñas, tokens ni tus modelos de terceros sin permiso.
Consulta CHANGELOG.md, SOURCE-LICENSES.md y PRIVACIDAD.md.
