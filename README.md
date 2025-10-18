# TL-Preentrega — EmpaquetAr

Landing para una tienda ficticia de cajas y kits de embalaje

## Estructura

- Estructura HTML: El HTML  esta dividido en etiquetas semanticas principales: `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`.
- Navegación: Implementacion de una lista desordenada con enlaces que simulan una navegación interna (`#inicio`, `#productos`, `#reseñas`, `#contacto`).
- Estilo de foco: reglas visibles para `:focus` y `:focus-visible` en enlaces y botones para mejorar navegación (no requerido, pero... aplicado igual).
- Catálogo de productos: tarjetas (`.card`) con una estructura consistente (`.card-body`) que asegura alineación visual y separación.
- Accesibilidad en tarjetas: imágenes con `alt`, botones "Agregar" con `aria-label` descriptivos, y los iconos decorativos marcados `aria-hidden="true"`.
- Contacto: formulario funcional apuntando a Formspree con `label` y campos requeridos.
- Multimedia: placeholder de video que, al clic, inserta un `<iframe>` con `title` y atributos `allow` adecuados (`autoplay`, `encrypted-media`).
- Estilos: `css/styles.css` usa variables CSS, tipografías de Google Fonts, Flexbox para productos y Grid para reseñas; media queries para movil.
- README y documentación: archivo `README.md` con propósito y descripción breve (este archivo).

## Archivos

- `index.html` — marcado semántico, header, navegación, secciones, tarjetas de producto, formulario y script del video.
- `css/styles.css` — variables, estilos generales, layout de tarjetas, media queries y reglas de foco.
- `README.md` — Incluimos un archivo que decribe y explica brevemente el propósito de la página.
- `Logo.png` - logo
- `playbutton.png` - imagen para usar en video

## Autor

- Damián Acosta