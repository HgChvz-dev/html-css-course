# 10 — Special Tags

## Tags learned

| Tag          | Purpose                                      |
| ------------ | -------------------------------------------- |
| `<details>`  | Collapsible content — expands on click       |
| `<summary>`  | Visible title of `<details>`                 |
| `<dialog>`   | Native HTML modal window                     |
| `<template>` | Inert HTML — not rendered until used with JS |
| `<progress>` | Progress bar                                 |
| `<meter>`    | Value meter within a defined range           |
| `<output>`   | Result of a calculation or action            |
| `<datalist>` | Suggestion list for an `<input>`             |
| `<search>`   | Semantic search container                    |

## Key attributes

| Attribute       | Used on      | Purpose                             |
| --------------- | ------------ | ----------------------------------- |
| `open`          | `<details>`  | Expanded by default                 |
| `open`          | `<dialog>`   | Visible by default                  |
| `value` / `max` | `<progress>` | Current progress and maximum        |
| `min` / `max`   | `<meter>`    | Value range                         |
| `low` / `high`  | `<meter>`    | Thresholds for warning zones        |
| `optimum`       | `<meter>`    | Ideal value                         |
| `list`          | `<input>`    | Links input to a `<datalist>` by id |

## How to open/close a dialog with JS

```javascript
document.getElementById('myDialog').showModal(); // open
document.getElementById('myDialog').close();     // close
```

## Rules learned

- `<summary>` must be the first child of `<details>`
- `<datalist>` id must match the `list` attribute of the input
- `<template>` content is not rendered — needs JS to be used
- `<meter>` is for known ranges — `<progress>` is for completion tracking
- `<output>` works with `oninput` on `<form>` for real-time calculations
- `<search>` is semantic — use it to wrap search forms

---

# 10 — Etiquetas Especiales

## Etiquetas aprendidas

| Etiqueta     | Para qué sirve                                    |
| ------------ | ------------------------------------------------- |
| `<details>`  | Contenido colapsable — se expande al hacer click  |
| `<summary>`  | Título visible del `<details>`                    |
| `<dialog>`   | Ventana modal nativa de HTML                      |
| `<template>` | HTML inerte — no se renderiza hasta usarlo con JS |
| `<progress>` | Barra de progreso                                 |
| `<meter>`    | Medidor de valor dentro de un rango definido      |
| `<output>`   | Resultado de un cálculo o acción                  |
| `<datalist>` | Lista de sugerencias para un `<input>`            |
| `<search>`   | Contenedor semántico de búsqueda                  |

## Atributos clave

| Atributo        | Se usa en    | Para qué sirve                              |
| --------------- | ------------ | ------------------------------------------- |
| `open`          | `<details>`  | Expandido por defecto                       |
| `open`          | `<dialog>`   | Visible por defecto                         |
| `value` / `max` | `<progress>` | Progreso actual y máximo                    |
| `min` / `max`   | `<meter>`    | Rango de valores                            |
| `low` / `high`  | `<meter>`    | Umbrales para zonas de advertencia          |
| `optimum`       | `<meter>`    | Valor ideal                                 |
| `list`          | `<input>`    | Vincula el input con un `<datalist>` por id |

## Cómo abrir/cerrar un dialog con JS

```javascript
document.getElementById('myDialog').showModal(); // abrir
document.getElementById('myDialog').close();     // cerrar
```

## Reglas aprendidas

- `<summary>` debe ser el primer hijo de `<details>`
- El `id` del `<datalist>` debe coincidir con el atributo `list` del input
- El contenido de `<template>` no se renderiza — necesita JS para usarse
- `<meter>` es para rangos conocidos — `<progress>` es para seguimiento de completado
- `<output>` funciona con `oninput` en `<form>` para cálculos en tiempo real
- `<search>` es semántico — úsalo para envolver formularios de búsqueda