# SOLUTECH INTEGRAL — sitio web

Sitio estático en español. No requiere instalar dependencias, configurar un servidor de aplicaciones ni usar una base de datos.

## Archivos

- `index.html`: página, estilos y comportamiento del formulario.
- `favicon.svg`: icono del sitio.
- `robots.txt`: permite que los buscadores rastreen el sitio.

## Publicar

1. Conserva estos archivos juntos en una misma carpeta.
2. Crea un sitio en un servicio de alojamiento para sitios estáticos y sube el contenido completo de la carpeta. Por ejemplo, puedes usar [Netlify Drop](https://app.netlify.com/drop) para una primera publicación manual, o cualquier alojamiento que acepte HTML estático.
3. Configura `index.html` como página de inicio y habilita HTTPS en el alojamiento.
4. Abre la dirección publicada desde un teléfono y un computador. Comprueba los enlaces de WhatsApp, llamada y correo, y envía un formulario de prueba.
5. Si conectas un dominio propio, configúralo en el alojamiento y comprueba la dirección con y sin `www`.

No se necesita compilar el sitio. Al hacer cambios, vuelve a subir los archivos actualizados.

## Formulario y datos

El formulario no almacena ni envía datos a un servidor. Prepara un mensaje para WhatsApp o abre el cliente de correo del visitante; este debe revisar y enviar el mensaje. Para registrar consultas automáticamente se necesitaría integrar un proveedor de formularios o un backend, además de informar al visitante sobre el tratamiento de sus datos.

## Antes de anunciar el sitio

- Confirma que el correo, el número y el enlace de WhatsApp son los canales que deseas publicar.
- Añade solo fotos de trabajos reales con autorización, y testimonios, certificaciones, marcas, garantías, zonas y horarios que puedas verificar.
- Si publicas fotos de instalaciones, evita mostrar rostros, direcciones, pantallas, códigos, placas u otros detalles sensibles.
- Revisa los requisitos de privacidad y protección de datos aplicables a tu país y a las instalaciones que realizas.
- Cuando tengas el dominio, añade la URL canónica, una imagen de vista previa para redes y un `sitemap.xml` con la dirección real.

El sitio usa enlaces relativos para sus recursos, de modo que puede alojarse en un dominio o directorio sin cambiar las rutas de archivos.
