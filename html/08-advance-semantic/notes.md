# 08 — Advanced Semantics

## Tags learned

| Tag         | Purpose                                                      |
| ----------- | ------------------------------------------------------------ |
| `<header>`  | Header of the page or a section. Can be used multiple times. |
| `<main>`    | Main content of the page. Only one per page.                 |
| `<footer>`  | Footer of the page or a section. Can be used multiple times. |
| `<aside>`   | Secondary content related to the main content.               |
| `<section>` | Groups thematic content. Needs a heading.                    |
| `<article>` | Independent and reusable content. Makes sense on its own.    |
| `<nav>`     | Main navigation block.                                       |
| `<address>` | Contact information for the author or owner.                 |
| `<hgroup>`  | Groups a title with its subtitle.                            |

## Key differences

| Tag         | When to use                                                           |
| ----------- | --------------------------------------------------------------------- |
| `<section>` | Part of something bigger — needs context to make sense                |
| `<article>` | Standalone — can be copied elsewhere and still make sense             |
| `<aside>`   | Related but not essential to understand the main content              |
| `<header>`  | Can appear inside `<article>` and `<section>`, not just at page level |
| `<footer>`  | Same as `<header>` — reusable inside sections and articles            |

## Rules learned

- `<main>` is unique — only one per page
- `<address>` goes inside `<footer>`, not loose in the page
- `<article>` can have its own `<header>` and `<footer>`
- `<hgroup>` wraps a heading + a subtitle `<p>` together
- `<nav>` is only for primary navigation — not every group of links

---

# 08 — Semántica Avanzada

## Etiquetas aprendidas

| Etiqueta    | Para qué sirve                                                      |
| ----------- | ------------------------------------------------------------------- |
| `<header>`  | Cabecera de la página o de una sección. Se puede usar varias veces. |
| `<main>`    | Contenido principal de la página. Solo uno por página.              |
| `<footer>`  | Pie de la página o de una sección. Se puede usar varias veces.      |
| `<aside>`   | Contenido secundario relacionado con el contenido principal.        |
| `<section>` | Agrupa contenido temático. Necesita un encabezado.                  |
| `<article>` | Contenido independiente y reutilizable. Tiene sentido solo.         |
| `<nav>`     | Bloque de navegación principal.                                     |
| `<address>` | Información de contacto del autor o dueño.                          |
| `<hgroup>`  | Agrupa un título con su subtítulo.                                  |

## Diferencias clave

| Etiqueta    | Cuándo usarla                                                           |
| ----------- | ----------------------------------------------------------------------- |
| `<section>` | Parte de algo más grande — necesita contexto para tener sentido         |
| `<article>` | Independiente — puede copiarse a otro lugar y sigue teniendo sentido    |
| `<aside>`   | Relacionado pero no esencial para entender el contenido principal       |
| `<header>`  | Puede ir dentro de `<article>` y `<section>`, no solo a nivel de página |
| `<footer>`  | Igual que `<header>` — reutilizable dentro de secciones y artículos     |

## Reglas aprendidas

- `<main>` es único — solo uno por página
- `<address>` va dentro de `<footer>`, no suelto en la página
- `<article>` puede tener su propio `<header>` y `<footer>`
- `<hgroup>` envuelve un heading + un subtítulo `<p>` juntos
- `<nav>` es solo para navegación principal — no para cualquier grupo de links