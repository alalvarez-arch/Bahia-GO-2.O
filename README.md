# BahiaGo 2.0

App PWA de gestión de turnos y equipo para hostelería de lujo.

## Subir a GitHub Pages

1. Crea un repositorio (ej. `bahiago` o `BahiaGo2.0`).
2. Sube **todo** el contenido de esta carpeta a la **raíz** del repo:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `.nojekyll`
   - `icons/` (carpeta completa)
   - `README.md`
3. **Settings → Pages → Deploy from a branch**
   - Branch: `main` (o `master`)
   - Folder: `/ (root)`
4. URL: `https://TU_USUARIO.github.io/NOMBRE_REPO/`

## Instalar en el móvil

### Android (Chrome)
Menú ⋮ → **Instalar aplicación** / **Añadir a la pantalla de inicio**.

### iPhone / iPad (Safari)
**Compartir** → **Añadir a pantalla de inicio**.

## Contenido

| Archivo | Descripción |
|---------|-------------|
| `index.html` | App completa BahiaGo 2.0 |
| `manifest.webmanifest` | Manifest PWA |
| `sw.js` | Service Worker (offline) |
| `icons/` | Iconos Android + Apple |
| `.nojekyll` | Requerido por GitHub Pages |

## Datos

Personal, horario y tareas se guardan en el dispositivo (localStorage).
Usa **Guardar** / **Cargar** / **WhatsApp** para el archivo `.json` entre dispositivos.
