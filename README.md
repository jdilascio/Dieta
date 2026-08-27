# Mis desayunos — GitHub Pages

Esta carpeta está lista para publicarse como sitio estático en GitHub Pages.

## Publicación rápida

1. Creá un repositorio nuevo en GitHub, por ejemplo `mis-desayunos`.
2. Subí **todos los archivos de esta carpeta a la raíz del repositorio**.
3. En GitHub, abrí:
   `Settings` → `Pages`.
4. En `Build and deployment`:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - Carpeta: `/(root)`
5. Guardá los cambios.
6. GitHub te mostrará la URL publicada cuando termine el despliegue.

## Instalar en iPhone

1. Abrí la URL de GitHub Pages en **Safari**.
2. Tocá el botón **Compartir**.
3. Elegí **Añadir a pantalla de inicio**.
4. Tocá **Añadir**.

Se abrirá como una web-app independiente desde el ícono de tu pantalla de inicio.

## Archivos

- `index.html`: aplicación.
- `manifest.webmanifest`: configuración instalable.
- `sw.js`: caché/offline básico.
- `icon-192.png` y `icon-512.png`: íconos.
- `.nojekyll`: indica a GitHub Pages que publique los archivos estáticos directamente.

## Nota sobre las fotos

Las imágenes de recetas se cargan desde Internet. La aplicación puede abrirse offline después de instalarse,
pero las fotos que no hayan quedado cacheadas pueden requerir conexión.
