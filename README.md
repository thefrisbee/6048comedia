# 6048 Comedia — Sitio Web

Landing page del **Curso Introducción a la Impro** de 6048 Comedia, Buenos Aires.

## Stack

- HTML + CSS + JS vanilla (sin frameworks)
- Fuentes: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Jost](https://fonts.google.com/specimen/Jost) via Google Fonts
- Hosting: GitHub Pages
- Dominio: Squarespace (apuntado a GitHub Pages via DNS)
- Imágenes: embebidas como base64 en el HTML

## Estructura del repo

```
/
├── index.html          # Landing page principal
├── favicon-32x32.png   # Favicon
├── styles/
│   └── tokens.css      # Variables de diseño (colores, tipografías)
├── BRANDBOOK.md        # Guía de identidad visual
└── README.md           # Este archivo
```

## Cómo deployar

1. Editás `index.html` localmente
2. Subís el archivo al repo (drag & drop en GitHub o `git push`)
3. GitHub Pages publica automáticamente en ~1 minuto

## Links

- **Sitio en vivo:** https://6048comedia.com
- **Repo:** https://github.com/thefrisbee/6048comedia
- **Instagram:** @6048comedia
- **WhatsApp contacto:** +54 9 11 6127 9303

## Próximas ediciones del curso

| Edición | Fechas | Estado |
|---------|--------|--------|
| Mayo 2026 | 6 · 13 · 20 · 27 de mayo | Completo |
| Junio–Julio 2026 | 17 · 24/6 · 1 · 8/7 | Abierto |

## Para actualizar el curso

Cuando hay una nueva edición:
1. Cambiar las fechas en el hero (`index.html`)
2. Agregar la edición anterior como "Completo" en la sección de cards
3. Actualizar el link de WhatsApp con el mensaje correcto
4. Actualizar el modal con las nuevas fechas
