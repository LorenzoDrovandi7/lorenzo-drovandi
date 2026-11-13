# Lorenzo Drovandi · Portfolio

Portfolio personal de Lorenzo Drovandi — desarrollador full-stack especializado en software a medida para el sector del hormigón.

Sitio estático sin build: `index.html` + `ld.webp`/`og.png` + legales. Para verlo en local:

```sh
python -m http.server 8080
```

## Despliegue

Opción A — GitHub Pages (gratis, repo público):

1. En GitHub: repo → Settings → Visibility → **Make public**.
2. Settings → Pages → Source: **Deploy from a branch**, rama `main`, carpeta `/`.
3. La URL queda en `https://lorenzodrovandi7.github.io/lorenzo-drovandi/`, que es la que usan el canonical, `og:url` y el JSON-LD.

Opción B — Vercel/Netlify con el repo en privado: importar el repo, sin comando de build, directorio de salida `/`.

Opción C — dominio propio: añadir un fichero `CNAME` con el dominio y apuntar el DNS según el proveedor elegido (las URL de canonical/sitemap/og:image hay que cambiarlas al dominio).

## Notas

- El formulario usa Formspree (`FORM_ENDPOINT` en `index.html`). Los envíos llegan al correo del titular.
- `sitemap.xml`: actualizar `lastmod` al publicar cambios.
