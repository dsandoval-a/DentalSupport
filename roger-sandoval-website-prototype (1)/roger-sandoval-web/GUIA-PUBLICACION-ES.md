# Publicación de la web de Roger Sandoval — guía rápida

## 1. Correo del formulario
- Crear una cuenta en Formspree y crear un formulario.
- Configurar como destinatario el correo comercial de Roger y verificarlo.
- Copiar el endpoint del formulario y reemplazar `REPLACE_WITH_FORM_ID` en `index.html`.
- Publicar y hacer una prueba real. Confirmar que el correo llega y revisar spam.
- El formulario es solo para consultas comerciales. No recibir datos, radiografías ni imágenes identificables de pacientes.

## 2. Dominio en GoDaddy
Ideas para buscar (no se ha verificado disponibilidad):
- `roger-sandoval.com`
- `sandovaldigitalplanning.com`
- `sandovalalignerplanning.com`

Elegir preferiblemente un `.com` corto y fácil de dictar por teléfono. Antes de pagar, revisar el precio de renovación y el total del plazo contratado, no solo la promoción inicial.

## 3. Publicar con Netlify
1. Crear una cuenta en Netlify.
2. Desplegar la carpeta del sitio que contiene `index.html`, `styles.css` y `script.js`.
3. Probar el enlace temporal de Netlify en computadora y celular.
4. En Netlify, abrir **Domain management** y agregar el dominio comprado en GoDaddy.
5. Copiar exactamente los registros DNS que Netlify indique para este sitio y agregarlos en la configuración DNS de GoDaddy.
6. Esperar la propagación DNS y la activación de HTTPS.
7. Probar el dominio con y sin `www`, además del formulario.

Guías oficiales:
- https://formspree.io/html/
- https://docs.netlify.com/domains-https/custom-domains/
- https://docs.netlify.com/manage/domains/configure-domains/configure-external-dns/
- https://www.godaddy.com/domains

**Estado actual:** el proyecto está preparado, pero el formulario, el dominio y el alojamiento aún requieren configuración por parte del propietario.
