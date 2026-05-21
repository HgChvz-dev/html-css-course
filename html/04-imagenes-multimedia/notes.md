# 04 — Images and Multimedia

## Tags learned

| Tag            | Purpose                                                |
| -------------- | ------------------------------------------------------ |
| `<img>`        | Displays an image. Self-closing.                       |
| `<figure>`     | Semantic container for an image with caption.          |
| `<figcaption>` | Description of the image inside `<figure>`.            |
| `<video>`      | Embeds a video player.                                 |
| `<audio>`      | Embeds an audio player.                                |
| `<source>`     | Defines the file source inside `<video>` or `<audio>`. |
| `<picture>`    | Responsive image with multiple sources by screen size. |

## Key attributes

| Attribute          | Used on                   | Purpose                                               |
| ------------------ | ------------------------- | ----------------------------------------------------- |
| `src`              | `<img>`                   | Image file path or URL                                |
| `alt`              | `<img>`                   | Text description — always required                    |
| `width` / `height` | `<img>`                   | Dimensions in pixels                                  |
| `loading="lazy"`   | `<img>`                   | Defers loading until image is visible                 |
| `controls`         | `<video>`, `<audio>`      | Shows play/pause/volume controls                      |
| `autoplay`         | `<video>`, `<audio>`      | Plays automatically on load                           |
| `muted`            | `<video>`                 | Starts muted (required for autoplay in most browsers) |
| `loop`             | `<video>`, `<audio>`      | Repeats the media                                     |
| `type`             | `<source>`                | File format (e.g. `video/mp4`, `audio/mp3`)           |
| `media`            | `<source>` in `<picture>` | Breakpoint condition                                  |
| `srcset`           | `<source>` in `<picture>` | Image URL for that breakpoint                         |

## Rules learned

- `alt` is mandatory on every `<img>` — never skip it
- `<video>` and `<audio>` do not accept `alt`
- Always use `<source>` inside `<video>` and `<audio>` with `type`
- `<picture>` must always end with an `<img>` as fallback
- `loading="lazy"` improves page performance

---

# 04 — Imágenes y Multimedia

## Etiquetas aprendidas

| Etiqueta       | Para qué sirve                                                  |
| -------------- | --------------------------------------------------------------- |
| `<img>`        | Muestra una imagen. Se cierra sola.                             |
| `<figure>`     | Contenedor semántico de imagen con descripción.                 |
| `<figcaption>` | Descripción de la imagen dentro de `<figure>`.                  |
| `<video>`      | Reproduce un video.                                             |
| `<audio>`      | Reproduce un audio.                                             |
| `<source>`     | Define la fuente del archivo dentro de `<video>` o `<audio>`.   |
| `<picture>`    | Imagen responsive con múltiples fuentes por tamaño de pantalla. |

## Atributos clave

| Atributo           | Se usa en                 | Para qué sirve                                                           |
| ------------------ | ------------------------- | ------------------------------------------------------------------------ |
| `src`              | `<img>`                   | Ruta o URL de la imagen                                                  |
| `alt`              | `<img>`                   | Descripción en texto — siempre obligatorio                               |
| `width` / `height` | `<img>`                   | Dimensiones en píxeles                                                   |
| `loading="lazy"`   | `<img>`                   | Carga diferida hasta que la imagen sea visible                           |
| `controls`         | `<video>`, `<audio>`      | Muestra controles de play/pausa/volumen                                  |
| `autoplay`         | `<video>`, `<audio>`      | Reproduce automáticamente al cargar                                      |
| `muted`            | `<video>`                 | Inicia sin sonido (necesario para autoplay en la mayoría de navegadores) |
| `loop`             | `<video>`, `<audio>`      | Repite el contenido                                                      |
| `type`             | `<source>`                | Formato del archivo (ej. `video/mp4`, `audio/mp3`)                       |
| `media`            | `<source>` en `<picture>` | Condición de breakpoint                                                  |
| `srcset`           | `<source>` en `<picture>` | URL de imagen para ese breakpoint                                        |

## Reglas aprendidas

- `alt` es obligatorio en todo `<img>` — nunca omitirlo
- `<video>` y `<audio>` no aceptan `alt`
- Siempre usar `<source>` dentro de `<video>` y `<audio>` con `type`
- `<picture>` siempre debe terminar con un `<img>` como fallback
- `loading="lazy"` mejora el rendimiento de la página