# SOLUTECH INTEGRAL — sitio web

Sitio estático en español. No requiere instalar dependencias, configurar un servidor de aplicaciones ni usar una base de datos.

## Archivos

- `index.html`: página, estilos y comportamiento del formulario.
- `favicon.svg`: icono del sitio.
- `robots.txt`: permite que los buscadores rastreen el sitio.

## Publicación y actualizaciones

El sitio se publica gratis con GitHub Pages desde la rama `main` de este repositorio. No requiere compilación. Cada commit que llega a GitHub inicia automáticamente una publicación; normalmente tarda unos minutos.

Esta carpeta está vinculada al repositorio `juanca23032003/solutech-integral`. El hook local `.githooks/post-commit` envía automáticamente a GitHub cada commit creado desde esta copia. Para habilitarlo en un clon nuevo:

```powershell
git clone https://github.com/juanca23032003/solutech-integral.git
cd solutech-integral
git config core.hooksPath .githooks
```

Los cambios guardados pero no confirmados no se publican. Revisa los cambios antes de confirmarlos: al crear un commit, este sitio público se actualizará automáticamente en GitHub Pages.

- Sitio: <https://juanca23032003.github.io/solutech-integral/>
- Repositorio: <https://github.com/juanca23032003/solutech-integral>

## Formulario y datos

El formulario no almacena ni envía datos a un servidor. Prepara un mensaje para WhatsApp o abre el cliente de correo del visitante; este debe revisar y enviar el mensaje. Para registrar consultas automáticamente se necesitaría integrar un proveedor de formularios o un backend, además de informar al visitante sobre el tratamiento de sus datos.

## Antes de anunciar el sitio

- Confirma que el correo, el número y el enlace de WhatsApp son los canales que deseas publicar.
- Añade solo fotos de trabajos reales con autorización, y testimonios, certificaciones, marcas, garantías, zonas y horarios que puedas verificar.
- Si publicas fotos de instalaciones, evita mostrar rostros, direcciones, pantallas, códigos, placas u otros detalles sensibles.
- Revisa los requisitos de privacidad y protección de datos aplicables a tu país y a las instalaciones que realizas.
- Cuando tengas el dominio, añade la URL canónica, una imagen de vista previa para redes y un `sitemap.xml` con la dirección real.

El sitio usa enlaces relativos para sus recursos.
