# 00 — Fundamentals: Base Structure

## What was learned

| Tag                                                                      | Purpose                                            |
| ------------------------------------------------------------------------ | -------------------------------------------------- |
| `<!DOCTYPE html>`                                                        | Declares HTML5. Always first.                      |
| `<html lang="es">`                                                       | Root of the document. `lang` defines the language. |
| `<head>`                                                                 | Page metadata. Not visible.                        |
| `<meta charset="UTF-8">`                                                 | Supports accents, ñ and emojis.                    |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Makes the page responsive on mobile.               |
| `<title>`                                                                | Text shown in the browser tab.                     |
| `<body>`                                                                 | All visible content goes here.                     |

## Key attributes

- `lang` — document language
- `charset` — character encoding
- `name` / `content` — key-value pair for metas
- `width=device-width` — width equals the device
- `initial-scale=1.0` — no initial zoom

## Golden rule

Every valid HTML file needs these 3 in the `<head>`:

1. `charset`
2. `viewport`
3. `title`

No viewport → broken on mobile.  
No charset → accents and ñ break.

---

# 00 — Fundamentos: Estructura Base

## Lo que se aprendió

| Etiqueta                                                                 | Para qué sirve                               |
| ------------------------------------------------------------------------ | -------------------------------------------- |
| `<!DOCTYPE html>`                                                        | Declara que es HTML5. Siempre primero.       |
| `<html lang="es">`                                                       | Raíz del documento. `lang` define el idioma. |
| `<head>`                                                                 | Metadatos de la página. No es visible.       |
| `<meta charset="UTF-8">`                                                 | Acepta tildes, ñ y emojis.                   |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Hace la página responsive en móvil.          |
| `<title>`                                                                | Texto de la pestaña del navegador.           |
| `<body>`                                                                 | Todo el contenido visible va aquí.           |

## Atributos clave

- `lang` — idioma del documento
- `charset` — codificación de caracteres
- `name` / `content` — par clave-valor de las metas
- `width=device-width` — ancho igual al dispositivo
- `initial-scale=1.0` — sin zoom inicial

## Regla de oro

Todo HTML válido necesita estas 3 en el `<head>`:

1. `charset`
2. `viewport`
3. `title`

Sin viewport → roto en móvil.  
Sin charset → tildes y ñ se rompen.