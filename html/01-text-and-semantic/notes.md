# 01 — Text and Semantics

## Tags learned

| Tag                     | Purpose                                               |
| ----------------------- | ----------------------------------------------------- |
| `<h1>` to `<h6>`        | Title hierarchy. Never skip levels.                   |
| `<p>`                   | Paragraph. Block elements cannot go inside.           |
| `<strong>`              | Important text (semantic bold).                       |
| `<em>`                  | Emphasis (semantic italic).                           |
| `<br>`                  | Line break.                                           |
| `<hr>`                  | Horizontal divider between sections.                  |
| `<blockquote>`          | Block quote from an external source.                  |
| `<cite>`                | Name of the source of a quote.                        |
| `<abbr title="...">`    | Abbreviation. Shows full meaning on hover.            |
| `<mark>`                | Highlighted text.                                     |
| `<small>`               | Secondary or legal text.                              |
| `<time datetime="...">` | Semantic date or time.                                |
| `<code>`                | Inline code.                                          |
| `<pre>`                 | Preformatted block. Preserves spaces and line breaks. |
| `<ul>` / `<li>`         | Unordered list. Cannot go inside `<p>`.               |
| `<article>`             | Independent content block.                            |
| `<footer>`              | Page footer. Must go inside `<body>`.                 |

## Key attributes

- `title` on `<abbr>` — shows full meaning on hover
- `datetime` on `<time>` — machine-readable date format (YYYY-MM-DD)

## Rules learned

- `<h3>` and other block elements cannot go inside `<p>`
- `<ul>` cannot go inside `<p>`
- `<footer>` must be inside `<body>`, not after it
- Use `<pre><code>` together for multiline code blocks
- `<strong>` = importance. `<em>` = vocal emphasis. Not the same.

---

# 01 — Texto y Semántica

## Etiquetas aprendidas

| Etiqueta                | Para qué sirve                                            |
| ----------------------- | --------------------------------------------------------- |
| `<h1>` al `<h6>`        | Jerarquía de títulos. Nunca saltarse niveles.             |
| `<p>`                   | Párrafo. No pueden ir elementos de bloque adentro.        |
| `<strong>`              | Texto importante (negrita semántica).                     |
| `<em>`                  | Énfasis (cursiva semántica).                              |
| `<br>`                  | Salto de línea.                                           |
| `<hr>`                  | Línea divisoria entre secciones.                          |
| `<blockquote>`          | Cita en bloque de una fuente externa.                     |
| `<cite>`                | Nombre de la fuente de una cita.                          |
| `<abbr title="...">`    | Abreviación. Muestra el significado al hacer hover.       |
| `<mark>`                | Texto resaltado.                                          |
| `<small>`               | Texto secundario o legal.                                 |
| `<time datetime="...">` | Fecha u hora semántica.                                   |
| `<code>`                | Código inline.                                            |
| `<pre>`                 | Bloque preformateado. Respeta espacios y saltos de línea. |
| `<ul>` / `<li>`         | Lista desordenada. No va dentro de `<p>`.                 |
| `<article>`             | Bloque de contenido independiente.                        |
| `<footer>`              | Pie de página. Debe ir dentro de `<body>`.                |

## Atributos clave

- `title` en `<abbr>` — muestra el significado completo al hacer hover
- `datetime` en `<time>` — formato de fecha para máquinas (YYYY-MM-DD)

## Reglas aprendidas

- `<h3>` y otros elementos de bloque no van dentro de `<p>`
- `<ul>` no va dentro de `<p>`
- `<footer>` va dentro de `<body>`, no después
- Usar `<pre><code>` juntos para bloques de código multilínea
- `<strong>` = importancia. `<em>` = énfasis de voz. No son lo mismo.