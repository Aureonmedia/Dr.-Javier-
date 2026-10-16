# Sitio web — Lic. Javier Mariscal

Sitio web de presentación profesional para el Lic. Javier Mariscal, con enfoque en psicoanálisis y neurociencia clínica.

## Contenido
- `index.html`: página principal del sitio.
- `assets/`: carpeta reservada para imágenes, estilos y otros recursos locales.

## Cómo visualizarlo
Abre `index.html` en un navegador. El sitio utiliza Tailwind CSS, Font Awesome y Google Fonts mediante CDN, por lo que necesita conexión a internet para cargar esas dependencias.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub.
2. Sube el contenido de esta carpeta (el archivo `index.html`, `README.md` y la carpeta `assets`).
3. En el repositorio, entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio y te muestre la URL.

## Antes de publicar
Revisa que el número de WhatsApp, el correo, las imágenes y los datos profesionales sean los definitivos. El enlace actual de WhatsApp es `https://wa.me/` y necesita el número correspondiente para funcionar correctamente.


## Imagen de perfil

El sitio utiliza una imagen local en `assets/javier-mariscal.svg`, así no depende de que cargue una imagen externa. Es una ilustración provisional: para mostrar la fotografía real, guarda la foto autorizada dentro de `assets` con el nombre `javier-mariscal.jpg` y cambia en `index.html` las rutas `assets/javier-mariscal.svg` por `assets/javier-mariscal.jpg`. Mantén las rutas relativas y respeta mayúsculas/minúsculas.
