# Portafolio de Anallely Garrido

Portafolio web estático sobre arquitectura de aprendizaje, diseño instruccional y plataformas de L&D.
Es HTML, CSS y JavaScript puros, sin dependencias ni proceso de compilación. La única petición externa es la tipografía Manrope de Google Fonts.

## Estructura

```
index.html          Página completa (estilos y scripts incluidos)
assets/img/         Capturas y fotos de los casos
.nojekyll           Evita que GitHub Pages procese el sitio con Jekyll
```

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `portafolio`.
2. Sube el contenido de esta carpeta a la raíz del repositorio, incluido `.nojekyll`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/portafolio/`.

Si nombras el repositorio `TU-USUARIO.github.io`, el sitio queda en `https://TU-USUARIO.github.io/`.

## Antes de publicar

- **Visibilidad.** GitHub Pages publica en internet. Con una cuenta gratuita, el repositorio debe ser público para usar Pages.
- **Buscadores.** `index.html` incluye `<meta name="robots" content="noindex, nofollow">`, para que Google no lo indexe. Si quieres que aparezca en búsquedas, borra esa línea.
- **Contenido.** Revisa que las capturas y fotos de `assets/img/` no muestren datos que no quieras hacer públicos, como nombres de colaboradores, información interna o personas que no hayan dado permiso.

## Editar

- Textos: edítalos directamente en `index.html`.
- Imágenes: reemplaza los archivos de `assets/img/` conservando el nombre, o cambia la ruta en el `<img>` correspondiente.
