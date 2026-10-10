# Arquetipo Digital

Landing estática para los servicios de arquitectura de software y consultoría .NET.

## Contenido

- `index.html`: página y estilos.
- `assets/`: imágenes utilizadas por la landing.
- `.agents/skills/landing-page-design/`: skill de diseño instalada para el proyecto.

## Publicar con GitHub Pages

El workflow `.github/workflows/pages.yml` despliega automáticamente el sitio cada vez que se actualiza la rama `main`. También se puede ejecutar manualmente desde **Actions → Deploy to GitHub Pages → Run workflow**.

Para activarlo la primera vez, abre **Settings → Pages** y selecciona **GitHub Actions** en **Build and deployment → Source**. El despliegue publicará `index.html` y los recursos de `assets/` en <https://clretamales.github.io/arquetipodigital/>.
