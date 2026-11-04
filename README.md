# Portafolio — Oscar Osorio

Página estática de portafolio con métricas reales de GitLab (commits, Merge
Requests, tasa de aceptación), caso de estudio del pipeline SDLC con agentes
de IA, y sección de proyectos personales y open source.

Un solo archivo (`index.html`), sin dependencias ni build: CSS y JS inline,
tema claro/oscuro automático según el sistema.

## Ver en local

Abrir `index.html` en el navegador. Nada más.

## Publicar en GitHub Pages

1. Crear el repositorio `devmaiter.github.io` en GitHub (público).
2. Apuntar este repo y subir:

   ```bash
   git remote add origin https://github.com/devmaiter/devmaiter.github.io.git
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Source: Deploy from a branch → main /(root)**.
4. La página queda en `https://devmaiter.github.io` en un par de minutos.

Con dominio propio después: **Settings → Pages → Custom domain** y un registro
CNAME en el DNS del dominio.
