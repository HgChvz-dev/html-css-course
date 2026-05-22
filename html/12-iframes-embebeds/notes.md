# 12 — Iframes and Embeds

## Tags learned

| Tag        | Purpose                                         |
| ---------- | ----------------------------------------------- |
| `<iframe>` | Embeds another web page inside your page        |
| `<embed>`  | Embeds external content (PDF, multimedia)       |
| `<object>` | Embeds external resources with fallback content |

## Key attributes for `<iframe>`

| Attribute          | Purpose                                         |
| ------------------ | ----------------------------------------------- |
| `src`              | URL of the content to embed                     |
| `width` / `height` | Dimensions                                      |
| `title`            | Accessibility description — always required     |
| `loading="lazy"`   | Defers loading until visible                    |
| `allowfullscreen`  | Allows fullscreen mode                          |
| `sandbox`          | Restricts iframe permissions                    |
| `allow`            | Specific permissions (camera, microphone, etc.) |

## sandbox values

| Value               | Meaning                                 |
| ------------------- | --------------------------------------- |
| `sandbox=""`        | Maximum restriction — blocks everything |
| `allow-scripts`     | Allows JavaScript                       |
| `allow-same-origin` | Allows cookies from same origin         |
| `allow-forms`       | Allows form submission                  |

## Rules learned

- `title` is mandatory on every `<iframe>` — required for accessibility
- `sandbox` without values blocks all permissions — add only what's needed
- `allowfullscreen` is needed for YouTube embeds to work in fullscreen
- `loading="lazy"` on iframes improves page performance
- `<embed>` needs `type` to tell the browser what kind of content it is
- Prefer `<iframe>` over `<embed>` for modern web content

---

# 12 — Iframes y Embeds

## Etiquetas aprendidas

| Etiqueta   | Para qué sirve                                       |
| ---------- | ---------------------------------------------------- |
| `<iframe>` | Incrusta otra página web dentro de la tuya           |
| `<embed>`  | Incrusta contenido externo (PDF, multimedia)         |
| `<object>` | Incrusta recursos externos con contenido de fallback |

## Atributos clave de `<iframe>`

| Atributo           | Para qué sirve                                     |
| ------------------ | -------------------------------------------------- |
| `src`              | URL del contenido a incrustar                      |
| `width` / `height` | Dimensiones                                        |
| `title`            | Descripción de accesibilidad — siempre obligatorio |
| `loading="lazy"`   | Carga diferida hasta que sea visible               |
| `allowfullscreen`  | Permite pantalla completa                          |
| `sandbox`          | Restringe permisos del iframe                      |
| `allow`            | Permisos específicos (cámara, micrófono, etc.)     |

## Valores de sandbox

| Valor               | Significado                       |
| ------------------- | --------------------------------- |
| `sandbox=""`        | Máxima restricción — bloquea todo |
| `allow-scripts`     | Permite JavaScript                |
| `allow-same-origin` | Permite cookies del mismo origen  |
| `allow-forms`       | Permite envío de formularios      |

## Reglas aprendidas

- `title` es obligatorio en todo `<iframe>` — necesario para accesibilidad
- `sandbox` sin valores bloquea todos los permisos — agregar solo lo necesario
- `allowfullscreen` es necesario para que los embeds de YouTube funcionen en pantalla completa
- `loading="lazy"` en iframes mejora el rendimiento de la página
- `<embed>` necesita `type` para indicarle al navegador qué tipo de contenido es
- Preferir `<iframe>` sobre `<embed>` para contenido web moderno