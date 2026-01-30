# OCR Danger Extreme

Landing page para la carrera de obstáculos **OCR Danger Extreme 2026** en Caleta de Fuste, Fuerteventura.

**[Ver sitio en vivo](https://danger-extreme.pages.dev)**

## Tecnologías

- **[Astro](https://astro.build)** - Framework web estático
- **[Tailwind CSS v4](https://tailwindcss.com)** - Estilos utility-first
- **[Cloudflare Pages](https://pages.cloudflare.com)** - Hosting

## Características

- Diseño responsive (móvil, tablet, desktop)
- Animaciones CSS personalizadas (logo pulsante, efecto glitch, partículas)
- SEO optimizado (meta tags, Open Graph, Twitter Cards, JSON-LD)
- Sitemap automático
- PWA ready (manifest.json)
- Accesibilidad (ARIA labels, prefers-reduced-motion)
- Rendimiento optimizado (preload, lazy loading, HTML/CSS minificado)

## Estructura

```
src/
├── components/
│   ├── Hero.astro        # Sección principal con logo y fecha
│   ├── EventInfo.astro   # Info del evento (fecha, lugar, distancia)
│   └── Categories.astro  # Categorías de carrera y footer
├── layouts/
│   └── Layout.astro      # Layout base con SEO
├── pages/
│   └── index.astro       # Página principal
└── styles/
    └── global.css        # Estilos globales y animaciones
```

## Desarrollo

```bash
# Instalar dependencias
bun install

# Servidor de desarrollo
bun run dev

# Build de producción
bun run build

# Preview del build
bun run preview
```

## Despliegue

```bash
# Build y deploy a Cloudflare Pages
bun run deploy
```

## Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Amarillo | `#D4A017` | Títulos, acentos |
| Rojo | `#E53935` | CTAs, "EXTREME" |
| Negro | `#0a0a0a` | Fondos |

## Evento

- **Fecha:** 1 de Agosto 2026
- **Lugar:** Caleta de Fuste, Fuerteventura
- **Distancia:** 6 km
- **Inscripciones:** Marzo 2026

## Categorías

- Elite 6km
- Pre-Elite 6km
- Popular Individual 6km
- Popular Parejas 6km

## Licencia

Todos los derechos reservados © 2026 OCR Danger Extreme
