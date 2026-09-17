# Ikigai Go — GitHub Pages

Este paquete está preparado para publicarse como sitio estático en GitHub Pages.

## Estructura
- `index.html` — aplicación principal
- `manifest.webmanifest` — configuración para instalarla como app web
- `assets/logo.png` — logo de Ikigai Go
- `.nojekyll` — evita procesamiento innecesario de Jekyll
- `README.md` — instrucciones

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `ikigai-go`.
2. Sube TODO el contenido de este ZIP al nivel raíz del repositorio.
   Importante: `index.html` debe quedar directamente en la raíz.
3. Ve a `Settings` → `Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub publique el sitio.
7. Abre la URL que GitHub te muestre.

## En iPhone
Abre la URL publicada en Safari → Compartir → Añadir a pantalla de inicio.
Si aparece la opción, activa `Abrir como app web`.

La versión actual guarda los datos de usuario/progreso localmente en el navegador. Para producción con cuentas reales y datos sincronizados entre dispositivos haría falta un backend.
