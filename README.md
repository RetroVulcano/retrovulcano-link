# RetroVulcano · Hub profesional

Web estática responsive para publicar en GitHub Pages.

## Archivos (todos en la raíz del repositorio)
- `index.html`: web completa (HTML, CSS y un pequeño script para el año y el resaltado del menú).
- `avatar.png` y `avatar.webp`: avatar (680×680); el WebP carga rápido y el PNG sirve de respaldo y de vista previa al compartir.
- `favicon.png`: icono de pestaña (128×128).
- `equipo.jpg`, `negocio.jpg`, `calidad.jpg`: imágenes de las tarjetas del perfil.
- `orbeautomata.jpg`, `pulsayjuega.jpg`: imágenes de las tarjetas de proyectos.
- `CNAME`: dominio personalizado `www.retrovulcano.link`.

## Publicar en GitHub Pages
1. Crea un repositorio público en GitHub, por ejemplo `retrovulcano-link`.
2. Sube los archivos (arrastrándolos a la web de GitHub sirve, no hay carpetas).
3. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. En **Custom domain**, escribe `www.retrovulcano.link` y guarda.
5. En tu proveedor DNS crea un registro `CNAME`: host `www`, destino `TUUSUARIO.github.io` (sin el nombre del repositorio).
6. Cuando GitHub lo permita, activa **Enforce HTTPS**.

Documentación oficial: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Antes de publicar
- Comprueba que el enlace de LinkedIn es correcto.
- Los proyectos enlazan a `https://www.orbeautomata.es/` y `https://pulsayjuega.es/`.
- La web no carga recursos de terceros (tipografías del sistema).
