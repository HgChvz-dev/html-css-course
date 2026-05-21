# 05 — Tables

## Tags learned

| Tag         | Purpose                                                       |
| ----------- | ------------------------------------------------------------- |
| `<table>`   | Table container.                                              |
| `<caption>` | Descriptive title of the table. Goes inside `<table>`, first. |
| `<thead>`   | Table header section.                                         |
| `<tbody>`   | Table body section.                                           |
| `<tfoot>`   | Table footer section.                                         |
| `<tr>`      | Table row.                                                    |
| `<th>`      | Header cell. Bold and centered by default.                    |
| `<td>`      | Data cell.                                                    |

## Key attributes

| Attribute     | Purpose                                            |
| ------------- | -------------------------------------------------- |
| `colspan="n"` | Cell spans n columns horizontally                  |
| `rowspan="n"` | Cell spans n rows vertically                       |
| `scope="col"` | `<th>` refers to a column — improves accessibility |
| `scope="row"` | `<th>` refers to a row — improves accessibility    |

## Rules learned

- `<caption>` goes inside `<table>`, before everything else
- `<thead>` contains the `<tr>` with `<th>` — not the `<tbody>`
- `<th>` always uses `scope` for accessibility
- `rowspan` removes the need to repeat cells — cleaner and semantic
- `colspan` merges cells horizontally — useful in `<tfoot>` summaries
- Every `<td>` and `<th>` must be properly closed

---

# 05 — Tablas

## Etiquetas aprendidas

| Etiqueta    | Para qué sirve                                                   |
| ----------- | ---------------------------------------------------------------- |
| `<table>`   | Contenedor de la tabla.                                          |
| `<caption>` | Título descriptivo de la tabla. Va dentro de `<table>`, primero. |
| `<thead>`   | Sección de encabezado de la tabla.                               |
| `<tbody>`   | Sección del cuerpo de la tabla.                                  |
| `<tfoot>`   | Sección del pie de la tabla.                                     |
| `<tr>`      | Fila de la tabla.                                                |
| `<th>`      | Celda de encabezado. Negrita y centrada por defecto.             |
| `<td>`      | Celda de datos.                                                  |

## Atributos clave

| Atributo      | Para qué sirve                                          |
| ------------- | ------------------------------------------------------- |
| `colspan="n"` | La celda ocupa n columnas horizontalmente               |
| `rowspan="n"` | La celda ocupa n filas verticalmente                    |
| `scope="col"` | `<th>` corresponde a una columna — mejora accesibilidad |
| `scope="row"` | `<th>` corresponde a una fila — mejora accesibilidad    |

## Reglas aprendidas

- `<caption>` va dentro de `<table>`, antes de todo lo demás
- `<thead>` contiene el `<tr>` con los `<th>` — no el `<tbody>`
- `<th>` siempre usa `scope` para accesibilidad
- `rowspan` evita repetir celdas — más limpio y semántico
- `colspan` fusiona celdas horizontalmente — útil en resúmenes del `<tfoot>`
- Todo `<td>` y `<th>` debe cerrarse correctamente