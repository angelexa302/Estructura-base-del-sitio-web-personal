# Sitio Web Personal — José Luis Navarta

Portafolio personal desarrollado como proyecto integrador de HTML, CSS, Bootstrap y control de versiones con Git/GitHub.

🔗 **Sitio desplegado:** https://angelexa302.github.io/Estructura-base-del-sitio-web-personal/

## Descripción

Sitio web personal de un docente de nivel primario especializado en informática educativa. Incluye presentación, reseña personal, proyectos realizados, habilidades técnicas y un formulario de contacto.

## Tecnologías utilizadas

- **HTML5** semántico (`header`, `main`, `nav`, `section`, `article`, `footer`)
- **CSS3**: variables (`:root`), Flexbox, CSS Grid con `grid-template-areas`, media queries mobile-first
- **Bootstrap 5.3** (vía CDN): navbar responsiva, carousel, modales
- **Google Fonts**: Poppins (títulos) y Roboto (cuerpo), con fallback `sans-serif`
- **Git / GitHub** para control de versiones

## Estructura del proyecto

```
/
├── index.html
├── assets/
│   ├── sobreMi.png
│   ├── yo.png
│   ├── habilidades.jpg
│   └── stock-photo-...jpg
├── pages/
│   ├── sobreMi.html
│   ├── proyectos.html
│   ├── habilidades.html
│   └── contacto.html
├── styles/
│   └── styles.css
└── README.md
```

## Características principales

- **Navbar responsiva de Bootstrap** en las 5 páginas, con menú hamburguesa por debajo de 992px (breakpoint `lg`).
- **Layout mobile-first**: el CSS base está pensado para móvil (secciones apiladas al 100% del ancho); las reglas dentro de `@media (min-width: 1024px)` agregan la versión de escritorio.
- **CSS Grid con `grid-template-areas`** en tres páginas completamente responsive (mobile y desktop):
  - `index.html` — layout de portada (hero, presentación, galería con carousel).
  - `pages/proyectos.html` — grilla de tarjetas de proyectos (1 columna en mobile, 3 en desktop).
  - `pages/habilidades.html` — imagen + contenido (apilado en mobile, 2 columnas en desktop).
- **Componentes de Bootstrap** integrados y personalizados con CSS propio para respetar la paleta del sitio: Navbar, Carousel (galería en `index.html`) y Modal (detalle de cada proyecto en `pages/proyectos.html`).
- **Paleta de colores propia** (definida en `styles.css` con variables CSS):
  - Primario `#1B263B` · Secundario `#415A77` · Acento `#E0A458`

## Cómo verlo localmente

Cloná el repositorio y abrí `index.html` en el navegador (no requiere instalación ni build):

```bash
git clone https://github.com/angelexa302/Estructura-base-del-sitio-web-personal.git
```

## Autor

José Luis Navarta
