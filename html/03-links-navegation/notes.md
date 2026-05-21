# 03 — Links and Navigation

## Tags learned

| Tag     | Purpose                                         |
| ------- | ----------------------------------------------- |
| `<a>`   | Link to another page, section, email, or phone. |
| `<nav>` | Semantic navigation block. Groups main links.   |

## Key attributes

| Attribute                   | Purpose                                          |
| --------------------------- | ------------------------------------------------ |
| `href`                      | Link destination (URL, `#id`, `mailto:`, `tel:`) |
| `target="_blank"`           | Opens link in a new tab                          |
| `rel="noopener noreferrer"` | Security when using `target="_blank"`            |
| `title`                     | Tooltip shown on hover                           |

## Link types

- **External:** `href="https://..."` — links to another website
- **Internal:** `href="#id"` — jumps to a section on the same page
- **Email:** `href="mailto:email@example.com"` — opens mail client
- **Phone:** `href="tel:+1234567890"` — calls from mobile

## Rules learned

- Always use `rel="noopener noreferrer"` with `target="_blank"` — security risk without it
- Every `<section>` must have a heading (`<h2>`, `<h3>`, etc.)
- `<nav>` is for main navigation only — not every group of links

---

# 03 — Links y Navegación

## Etiquetas aprendidas

| Etiqueta | Para qué sirve                                                |
| -------- | ------------------------------------------------------------- |
| `<a>`    | Enlace a otra página, sección, correo o teléfono.             |
| `<nav>`  | Bloque de navegación semántico. Agrupa los links principales. |

## Atributos clave

| Atributo                    | Para qué sirve                                   |
| --------------------------- | ------------------------------------------------ |
| `href`                      | Destino del link (URL, `#id`, `mailto:`, `tel:`) |
| `target="_blank"`           | Abre el link en una nueva pestaña                |
| `rel="noopener noreferrer"` | Seguridad al usar `target="_blank"`              |
| `title`                     | Tooltip al hacer hover                           |

## Tipos de links

- **Externo:** `href="https://..."` — enlaza a otro sitio web
- **Interno:** `href="#id"` — salta a una sección de la misma página
- **Email:** `href="mailto:correo@ejemplo.com"` — abre el cliente de correo
- **Teléfono:** `href="tel:+1234567890"` — llama desde móvil

## Reglas aprendidas

- Siempre usar `rel="noopener noreferrer"` con `target="_blank"` — sin esto es un riesgo de seguridad
- Toda `<section>` debe tener un encabezado (`<h2>`, `<h3>`, etc.)
- `<nav>` es solo para navegación principal — no para cualquier grupo de links