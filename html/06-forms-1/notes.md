# 06 — Forms Part 1

## Tags learned

| Tag          | Purpose                                                 |
| ------------ | ------------------------------------------------------- |
| `<form>`     | Form container. All inputs must go inside.              |
| `<fieldset>` | Groups related fields visually and semantically.        |
| `<legend>`   | Title for a `<fieldset>`.                               |
| `<label>`    | Descriptive text for an input. Always linked via `for`. |
| `<input>`    | Data entry field. Behavior changes with `type`.         |
| `<textarea>` | Multiline text field.                                   |
| `<select>`   | Dropdown list.                                          |
| `<option>`   | Single option inside `<select>`.                        |
| `<optgroup>` | Groups options inside `<select>` with a label.          |
| `<button>`   | Clickable button. Behavior changes with `type`.         |

## Input types learned

| type       | Purpose                          |
| ---------- | -------------------------------- |
| `text`     | Plain text                       |
| `email`    | Email address — validates format |
| `password` | Hidden text                      |
| `number`   | Numeric input                    |
| `tel`      | Phone number                     |
| `date`     | Date picker                      |
| `url`      | URL — validates format           |
| `checkbox` | Multiple selection               |
| `radio`    | Single selection from a group    |
| `file`     | File upload                      |

## Key attributes

| Attribute            | Purpose                                        |
| -------------------- | ---------------------------------------------- |
| `action`             | Where the form sends data                      |
| `method`             | How it sends: `get` or `post`                  |
| `for`                | Links `<label>` to input's `id`                |
| `id`                 | Unique identifier — required for `for` to work |
| `name`               | Key sent to the server                         |
| `placeholder`        | Helper text inside the input                   |
| `value`              | Default value                                  |
| `required`           | Field cannot be empty on submit                |
| `rows` / `cols`      | Size of `<textarea>`                           |
| `type` on `<button>` | `submit`, `reset`, or `button`                 |

## Rules learned

- All inputs must be inside `<form>` to be submitted
- Every `<label>` must have `for` matching the input's `id`
- Every `<input>` must have `id` and `name`
- `<fieldset>` outside `<form>` is just visual — data won't be sent
- `<optgroup>` does not need a `value` — it's only a visual label

---

# 06 — Formularios Parte 1

## Etiquetas aprendidas

| Etiqueta     | Para qué sirve                                                |
| ------------ | ------------------------------------------------------------- |
| `<form>`     | Contenedor del formulario. Todos los inputs deben ir adentro. |
| `<fieldset>` | Agrupa campos relacionados visual y semánticamente.           |
| `<legend>`   | Título de un `<fieldset>`.                                    |
| `<label>`    | Texto descriptivo de un input. Siempre vinculado con `for`.   |
| `<input>`    | Campo de entrada. El comportamiento cambia con `type`.        |
| `<textarea>` | Campo de texto multilínea.                                    |
| `<select>`   | Lista desplegable.                                            |
| `<option>`   | Opción individual dentro de `<select>`.                       |
| `<optgroup>` | Agrupa opciones dentro de `<select>` con una etiqueta.        |
| `<button>`   | Botón clickeable. El comportamiento cambia con `type`.        |

## Tipos de input aprendidos

| type       | Para qué sirve                      |
| ---------- | ----------------------------------- |
| `text`     | Texto plano                         |
| `email`    | Correo electrónico — valida formato |
| `password` | Texto oculto                        |
| `number`   | Número                              |
| `tel`      | Teléfono                            |
| `date`     | Selector de fecha                   |
| `url`      | URL — valida formato                |
| `checkbox` | Selección múltiple                  |
| `radio`    | Selección única en un grupo         |
| `file`     | Subida de archivos                  |

## Atributos clave

| Atributo             | Para qué sirve                                          |
| -------------------- | ------------------------------------------------------- |
| `action`             | A dónde envía los datos el formulario                   |
| `method`             | Cómo los envía: `get` o `post`                          |
| `for`                | Vincula `<label>` con el `id` del input                 |
| `id`                 | Identificador único — necesario para que `for` funcione |
| `name`               | Clave que se envía al servidor                          |
| `placeholder`        | Texto de ayuda dentro del input                         |
| `value`              | Valor por defecto                                       |
| `required`           | El campo no puede estar vacío al enviar                 |
| `rows` / `cols`      | Tamaño del `<textarea>`                                 |
| `type` en `<button>` | `submit`, `reset`, o `button`                           |

## Reglas aprendidas

- Todos los inputs deben estar dentro de `<form>` para enviarse
- Todo `<label>` debe tener `for` que coincida con el `id` del input
- Todo `<input>` debe tener `id` y `name`
- Un `<fieldset>` fuera del `<form>` es solo visual — los datos no se envían
- `<optgroup>` no necesita `value` — es solo una etiqueta visual