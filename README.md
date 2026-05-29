# Calculadora 100% 3D

Aplicacion web offline para calcular presupuestos de impresion 3D, registrar ventas mensuales, gastos, productos guardados y costos internos.

## Abrir localmente

Abrir `index.html` o `abrir-app-offline.bat`.

## Publicar en GitHub Pages

1. Crear un repositorio en GitHub.
2. Subir estos archivos al repositorio.
3. En GitHub, ir a `Settings > Pages`.
4. En `Build and deployment`, elegir:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guardar.

La URL queda con este formato:

`https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

## Archivos importantes

- `index.html`: aplicacion principal.
- `manifest.webmanifest`: datos de app instalable.
- `sw.js`: cache offline.
- `assets/`: imagenes locales.
- `icons/`: icono de la app.
