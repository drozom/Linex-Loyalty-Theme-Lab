# Linex Loyalty — Theme Lab

Sitio estático publicado en GitHub Pages para que el equipo revise las candidatas de color y las direcciones de diseño de Linex Loyalty sin necesitar acceso a Claude.

- `index.html` — el Theme Lab (13 candidatas de acento, 3 modos de fondo, comparación lado a lado, contraste WCAG, distancia ΔE contra Travel/Go/Violet, y el selector de Dirección: Flat accent / Aurora — Light / Aurora — Dark).
- `Linex-Loyalty-Home-Aurora-Light.html` y `Linex-Loyalty-Home-Aurora-Content.html` — los dos mockups de dirección Aurora, mostrados dentro del Theme Lab vía iframe. No los renombres ni los muevas de esta carpeta: el Theme Lab los referencia por nombre de archivo relativo.

## Este repo es un export, no la fuente

La fuente editable vive en el proyecto interno, en `brand-system/color-studies/` (los mismos 3 archivos). Para publicar una actualización:

1. Copia los 3 archivos actualizados desde `brand-system/color-studies/` a esta carpeta (el de Theme Lab renómbralo a `index.html`).
2. `git add -A && git commit -m "..." && git push`

## Qué NO está aquí (a propósito)

Los PDFs de estrategia de marca (marcados CONFIDENTIAL) y `brand-tokens.json` (artefacto interno) se quedan fuera de este repo público — viven solo en el proyecto interno.
