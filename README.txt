# Terminal de Etiquetas ORGBRO — PWA FINAL

## Contenido
- index.html — aplicación actual.
- manifest.json — instalación como aplicación.
- service-worker.js — caché y soporte offline básico.

## Publicación
Los tres archivos deben estar en la misma carpeta y publicarse mediante HTTPS.
La página inicial debe ser `index.html`.

## GitHub Pages
1. Crea un repositorio.
2. Sube `index.html`, `manifest.json` y `service-worker.js` a la raíz.
3. Activa Settings → Pages.
4. Selecciona la rama principal y `/root` (o `/docs` si corresponde).
5. Abre la URL HTTPS generada.

## Android
Abre la URL con Chrome y selecciona "Instalar aplicación" o "Añadir a pantalla de inicio".

## iPhone
Abre la URL con Safari → Compartir → "Añadir a pantalla de inicio".

## Importante
La aplicación actual utiliza recursos externos (Tailwind, html2canvas y Google Fonts).
La interfaz y el App Shell se almacenan en caché, pero el funcionamiento completamente
offline de esos recursos externos depende de que hayan sido cargados previamente.
La impresión directa hacia la ORGBRO X3 todavía no está implementada; la aplicación
genera PNG para su posterior impresión.
