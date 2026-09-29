# Octavo Día · Landing page (demo)

Landing de conversión para **Octavo Día, agencia creativa en Lima**. Está hecha con HTML, CSS y JavaScript, sin librerías y en un solo archivo (`index.html`).

**Demo en vivo:** se activa con GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Qué incluye
- Diseño mobile-first con la identidad del manual de marca v1.0: Anton + DM Sans, coral `#FB515A`, negro `#201E1F` y crudo `#F3EDE3`.
- Secciones: hero, franja de servicios, valores, servicios, planes por tipo de cliente, casos, preguntas frecuentes y formulario de cotización que abre WhatsApp.
- Animaciones con `transform` y `opacity`, `IntersectionObserver` y `requestAnimationFrame`. Respetan `prefers-reduced-motion`.
- Contraste revisado con WCAG AA: los botones coral llevan texto negro (5,07:1).
- Preparada para campañas: espacios para Meta Pixel y GA4, eventos al hacer clic en WhatsApp y parámetros UTM añadidos al mensaje.

## Antes de publicar en producción
Busca `EDITAR` en `index.html`:
- `CONFIG.whatsapp`: número con código de país, sin "+" (por ejemplo, `51987654321`).
- IDs de Meta Pixel y GA4.
- Textos entre corchetes: casos, testimonio, precios, plazos, RUC y datos de contacto reales.
- Logo e isotipo en SVG oficial, y favicon.
- Enlaces legales: política de privacidad, términos y Libro de Reclamaciones (validar con un profesional).

> Demo con contenido de ejemplo. Los espacios entre [corchetes] deben reemplazarse por información real del cliente.
