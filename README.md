# La Cartelera del Club — Julio 2026

Sitio de una sola página con las actividades de julio del Club Aprender de Grandes. Es un único archivo `index.html` autocontenido (imágenes embebidas, sin dependencias externas salvo Google Fonts).

## Cómo subirlo a GitHub

1. Creá un repositorio nuevo en GitHub (público, si querés usar GitHub Pages gratis).
2. Subí el archivo `index.html` a la raíz del repo:
   - Desde la web: **Add file → Upload files** y arrastrá `index.html`.
   - Desde la terminal:
     ```bash
     git init
     git add index.html
     git commit -m "Cartelera de julio"
     git branch -M main
     git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
     git push -u origin main
     ```

## Cómo publicarlo con GitHub Pages (para tener un link público)

1. En el repo, andá a **Settings → Pages**.
2. En "Source" elegí la rama `main` y la carpeta `/ (root)`.
3. Guardá. En un minuto vas a tener el sitio publicado en:
   `https://TU-USUARIO.github.io/TU-REPO/`

Como el archivo ya se llama `index.html`, no necesitás configurar nada más: GitHub Pages lo sirve automáticamente como página principal.

## Notas

- Todos los botones de las actividades apuntan a `https://klouser.app/aprenderdegrandes`.
- El diseño es responsive (probado en 320px, 375px, 414px, 768px y 1440px de ancho).
- Si más adelante querés actualizar el contenido, pedime los cambios y te vuelvo a generar el `index.html`.
