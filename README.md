# DGLab Landing — Variant "rno1-like"

Editorial, tipografía grande, bloques alternados y paleta ocre.

## Paleta
- Fondo: #0B0B0B
- Texto: #E8E6E3
- Oro: #C7A042
- Oro claro: #E2C574
- Oro oscuro: #8C6A1F

## Estructura
- `index.html`: todo el layout con Tailwind CDN
- `assets/`: logo + placeholders SVG

## Editar
- Cambia textos directamente en `index.html`
- Busca `brand: { ... }` en el bloque `tailwind.config` para ajustar colores
- Reemplaza placeholders en `assets/` por imágenes reales (webp/png/jpg)

## Publicar
Funciona como sitio estático:
- Netlify (drag & drop)
- Vercel (importar repo)
- GitHub Pages (root)
- Cualquier hosting con carpeta `public_html`

## Formularios
El form es demo (localStorage). Para producción: Netlify Forms, Formspree, Supabase, Firebase o tu backend.

