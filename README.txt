# Terminal de Etiquetas ORGBRO — PWA

## Archivos
- `index.html`: aplicación.
- `manifest.json`: configuración para instalarla como app.
- `service-worker.js`: caché/offline básico.

## Publicación
Sube los tres archivos a un hosting HTTPS que sirva `index.html` como página inicial.

## Android
Abre la URL con Chrome y selecciona "Instalar aplicación" o "Añadir a pantalla de inicio".

## iPhone
Abre la URL con Safari → Compartir → "Añadir a pantalla de inicio".

## Nota
La aplicación sigue generando PNG mediante html2canvas y conserva sus datos con localStorage. La impresión directa hacia la ORGBRO X3 todavía no está implementada.
