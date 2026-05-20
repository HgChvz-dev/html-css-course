# 00 — Fundamentos: Estructura Base

## Etiquetas aprendidas

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

Todo HTML válido necesita estas 3 metas en el `<head>`:
1. `charset`
2. `viewport`
3. `title`

Sin viewport → roto en móvil.  
Sin charset → tildes y ñ se rompen.