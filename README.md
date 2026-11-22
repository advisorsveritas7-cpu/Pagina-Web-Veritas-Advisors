# Página web de Veritas Advisors

Sitio estático (un solo archivo `index.html`) publicado en Netlify.

## Prueba gratuita

- Sección **Prueba gratis** (`#prueba`) con una tarjeta por programa, botón **Prueba gratis** en cada producto del catálogo y en el panel **Ingresar**.
- Enlaces directos para compartir en anuncios, WhatsApp o correo:
  - `https://veritas-advisors.net/?prueba=planillas`
  - `https://veritas-advisors.net/?prueba=gasmapa`
  - `https://veritas-advisors.net/?prueba=contable`
  - `https://veritas-advisors.net/?prueba=gestion`
- El formulario usa **Netlify Forms** (nombre `solicitud`). Las solicitudes aparecen en Netlify → *Forms*. Para recibirlas por correo: *Site configuration → Forms → Form notifications → Email notification* → `informes@veritas-advisors.net`.
- Si el envío falla, el cliente ve enlaces para mandar la solicitud por correo o WhatsApp (980 990 574).

## Qué editar en `index.html`

- `SISTEMAS`: dirección (`url`) de cada sistema para el botón **Ingresar**. GasMapa aún no tiene `url`.
- `PRUEBAS`: programas con prueba, días de prueba y si ya están `enLinea`.
- `PRECIOS_URL`: enlace CSV de la hoja de Google con los precios.
