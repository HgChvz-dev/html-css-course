# 09 — Meta Tags and SEO

## Tags and attributes learned

| Tag                                 | Purpose                                               |
| ----------------------------------- | ----------------------------------------------------- |
| `<meta name="description">`         | Page description shown in search results              |
| `<meta name="author">`              | Author of the page                                    |
| `<meta name="robots">`              | Tells search engines to index or not                  |
| `<meta property="og:title">`        | Title when sharing on social media                    |
| `<meta property="og:description">`  | Description when sharing on social media              |
| `<meta property="og:image">`        | Image when sharing on social media                    |
| `<meta property="og:url">`          | Canonical URL when sharing                            |
| `<meta property="og:type">`         | Content type (website, article, etc.)                 |
| `<meta name="twitter:card">`        | Card type on Twitter/X                                |
| `<meta name="twitter:title">`       | Title on Twitter/X                                    |
| `<meta name="twitter:description">` | Description on Twitter/X                              |
| `<meta name="twitter:image">`       | Image on Twitter/X                                    |
| `<link rel="canonical">`            | Tells search engines the main URL to avoid duplicates |
| `<link rel="icon">`                 | Page favicon                                          |

## robots values

| Value               | Meaning                             |
| ------------------- | ----------------------------------- |
| `index, follow`     | Index the page and follow its links |
| `noindex, nofollow` | Don't index and don't follow links  |
| `noindex, follow`   | Don't index but follow links        |

## twitter:card values

| Value                 | Meaning              |
| --------------------- | -------------------- |
| `summary`             | Small card with text |
| `summary_large_image` | Large image card     |

## Rules learned

- All meta tags go inside `<head>`
- `name` is for standard metas, `property` is for Open Graph
- `og:image` must be an absolute URL — not a relative path
- `<link rel="canonical">` prevents duplicate content penalties in Google
- Twitter Card and Open Graph are different systems — both needed for full coverage

---

# 09 — Meta Tags y SEO

## Etiquetas y atributos aprendidos

| Etiqueta                            | Para qué sirve                                                   |
| ----------------------------------- | ---------------------------------------------------------------- |
| `<meta name="description">`         | Descripción de la página en resultados de búsqueda               |
| `<meta name="author">`              | Autor de la página                                               |
| `<meta name="robots">`              | Le dice a los buscadores si indexar o no                         |
| `<meta property="og:title">`        | Título al compartir en redes sociales                            |
| `<meta property="og:description">`  | Descripción al compartir en redes sociales                       |
| `<meta property="og:image">`        | Imagen al compartir en redes sociales                            |
| `<meta property="og:url">`          | URL canónica al compartir                                        |
| `<meta property="og:type">`         | Tipo de contenido (website, article, etc.)                       |
| `<meta name="twitter:card">`        | Tipo de card en Twitter/X                                        |
| `<meta name="twitter:title">`       | Título en Twitter/X                                              |
| `<meta name="twitter:description">` | Descripción en Twitter/X                                         |
| `<meta name="twitter:image">`       | Imagen en Twitter/X                                              |
| `<link rel="canonical">`            | Le dice a Google cuál es la URL principal para evitar duplicados |
| `<link rel="icon">`                 | Favicon de la página                                             |

## Valores de robots

| Valor               | Significado                        |
| ------------------- | ---------------------------------- |
| `index, follow`     | Indexa la página y sigue sus links |
| `noindex, nofollow` | No indexa y no sigue links         |
| `noindex, follow`   | No indexa pero sigue links         |

## Valores de twitter:card

| Valor                 | Significado            |
| --------------------- | ---------------------- |
| `summary`             | Card pequeña con texto |
| `summary_large_image` | Card con imagen grande |

## Reglas aprendidas

- Todas las meta tags van dentro de `<head>`
- `name` es para metas estándar, `property` es para Open Graph
- `og:image` debe ser una URL absoluta — no una ruta relativa
- `<link rel="canonical">` evita penalizaciones por contenido duplicado en Google
- Twitter Card y Open Graph son sistemas distintos — se necesitan ambos para cobertura completa