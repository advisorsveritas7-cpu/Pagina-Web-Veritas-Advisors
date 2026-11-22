# Página web de Veritas Advisors

Sitio estático (un solo archivo `index.html`) publicado en DigitalOcean App Platform. Cada cambio que entra a `main` se publica solo (`.do/app.yaml`).

## Prueba gratuita

- Sección **Prueba gratis** (`#prueba`) con una tarjeta por programa, botón **Prueba gratis** en cada producto del catálogo y en el panel **Ingresar**.
- Enlaces directos para compartir en anuncios, WhatsApp o correo:
  - `https://veritas-advisors.net/?prueba=planillas`
  - `https://veritas-advisors.net/?prueba=gasmapa`
  - `https://veritas-advisors.net/?prueba=contable`
  - `https://veritas-advisors.net/?prueba=gestion`
- El formulario envía cada solicitud por correo a `informes@veritas-advisors.net` mediante [FormSubmit](https://formsubmit.co) (constante `FORM_URL`). La primera vez llega a esa casilla un correo de activación: hay que abrirlo y confirmar una sola vez.
- Si el envío falla, el cliente ve enlaces para mandar la solicitud por correo o WhatsApp (980 990 574).

## Qué editar en `index.html`

- `SISTEMAS`: dirección (`url`) de cada sistema para el botón **Ingresar**. GasMapa aún no tiene `url`.
- `PRUEBAS`: programas con prueba, días de prueba y si ya están `enLinea`.
- `PRECIOS_URL`: enlace CSV de la hoja de Google con los precios.
