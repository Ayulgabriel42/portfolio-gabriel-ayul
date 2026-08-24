# Portfolio - Gabriel Ayul

Landing page personal (HTML estático).

## Deploy

- Repo GitHub: https://github.com/Ayulgabriel42/portfolio-gabriel-ayul
- Proyecto Vercel: `gabriel-ayul-portfolio`
- Conectado por Git: cada `git push` a `master` dispara un deploy automático en Vercel.

## Flujo para actualizar el sitio

```bash
cd outputs
git add -A
git commit -m "mensaje del cambio"
git push
```

Vercel detecta el push y redeploya solo (ver Project Settings > Git en el dashboard de Vercel).

## Estructura

- `index.html` — página principal
- `img/` — imágenes y video de proyectos
- `cv-gabriel-ayul.pdf` — CV (actualmente sin usar; el botón "Descargar CV" apunta a Google Drive)
