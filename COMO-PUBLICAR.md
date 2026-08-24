# Cómo publicar tu landing en Vercel (gratis)

Archivos incluidos:
- `index.html` — la landing completa (un solo archivo, sin dependencias externas salvo Google Fonts).
- `cv-gabriel-ayul.pdf` — tu CV, usado por el botón "Descargar CV".

## Opción A — Sin instalar nada (arrastrar y soltar)

1. Entrá a https://vercel.com y creá una cuenta gratis (podés usar tu cuenta de Google o GitHub).
2. Una vez adentro, andá a "Add New… → Project".
3. Elegí la opción de subir una carpeta (drag and drop) y arrastrá la carpeta que contiene `index.html` y `cv-gabriel-ayul.pdf`.
4. Vercel te da un link gratuito al toque, algo como `gabriel-ayul.vercel.app`.

## Opción B — Con GitHub (recomendado a mediano plazo)

1. Subí estos dos archivos a un repositorio nuevo en GitHub (por ejemplo `gabriel-ayul-landing`).
2. En Vercel: "Add New… → Project" → conectá tu cuenta de GitHub → elegí el repo.
3. Dejá la configuración por defecto (no hace falta build command, es HTML estático) y Deploy.
4. Cada vez que actualices el repo, Vercel republica el sitio solo.

## Conectar tu propio dominio (opcional)

1. Comprá el dominio en un proveedor (NIC.ar para `.com.ar`, o Namecheap/GoDaddy para `.com`).
2. En el proyecto de Vercel: Settings → Domains → agregá tu dominio.
3. Vercel te da 1-2 registros DNS (tipo A o CNAME) para cargar en el panel de tu proveedor de dominio.
4. Propaga en minutos u horas. Vercel emite el certificado HTTPS automáticamente.

## Antes de publicar, revisá:

- El botón de LinkedIn apunta a `linkedin.com/in/gabriel-ayul` — reemplazalo por tu URL real de perfil si es distinta (buscá tu usuario en la barra de tu perfil de LinkedIn).
- Si querés cambiar textos, colores o agregar una foto tuya, decime y lo ajusto.
