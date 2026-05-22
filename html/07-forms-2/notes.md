# 07 — Forms Part 2: Validation and Attributes

## Key attributes learned

| Attribute                 | Used on             | Purpose                                  |
| ------------------------- | ------------------- | ---------------------------------------- |
| `required`                | any input           | Field cannot be empty on submit          |
| `min` / `max`             | `number`, `date`    | Minimum and maximum value                |
| `minlength` / `maxlength` | `text`, `textarea`  | Minimum and maximum character length     |
| `pattern`                 | `text`              | Regex to validate format                 |
| `disabled`                | any input           | Field is disabled — not sent to server   |
| `readonly`                | any input           | Read only — still sent to server         |
| `autofocus`               | any input           | Automatically focused on page load       |
| `autocomplete`            | `form`, input       | Enables or disables browser autocomplete |
| `multiple`                | `email`, `file`     | Accepts multiple values                  |
| `accept`                  | `file`              | Allowed file types                       |
| `checked`                 | `checkbox`, `radio` | Checked by default                       |
| `selected`                | `option`            | Selected by default in `<select>`        |
| `step`                    | `number`, `date`    | Allowed increment                        |

## Rules learned

- `disabled` — field is visible but not editable and NOT sent to server
- `readonly` — field is not editable but IS sent to server
- `pattern=".{8,}"` — regex for minimum 8 characters
- `checked` goes on `<input>`, `selected` goes on `<option>`
- `min="2026-05-22"` on `type="date"` prevents past dates
- `step="10"` on `type="number"` only allows multiples of 10
- `accept=".json,.yaml"` filters files in the OS picker — not a security measure

---

# 07 — Formularios Parte 2: Validación y Atributos

## Atributos clave aprendidos

| Atributo                  | Se usa en           | Para qué sirve                                     |
| ------------------------- | ------------------- | -------------------------------------------------- |
| `required`                | cualquier input     | El campo no puede estar vacío al enviar            |
| `min` / `max`             | `number`, `date`    | Valor mínimo y máximo                              |
| `minlength` / `maxlength` | `text`, `textarea`  | Longitud mínima y máxima en caracteres             |
| `pattern`                 | `text`              | Regex para validar el formato                      |
| `disabled`                | cualquier input     | Campo deshabilitado — no se envía al servidor      |
| `readonly`                | cualquier input     | Solo lectura — sí se envía al servidor             |
| `autofocus`               | cualquier input     | Se enfoca automáticamente al cargar la página      |
| `autocomplete`            | `form`, input       | Activa o desactiva el autocompletado del navegador |
| `multiple`                | `email`, `file`     | Acepta múltiples valores                           |
| `accept`                  | `file`              | Tipos de archivo permitidos                        |
| `checked`                 | `checkbox`, `radio` | Marcado por defecto                                |
| `selected`                | `option`            | Seleccionado por defecto en `<select>`             |
| `step`                    | `number`, `date`    | Incremento permitido                               |

## Reglas aprendidas

- `disabled` — visible pero no editable y NO se envía al servidor
- `readonly` — no editable pero SÍ se envía al servidor
- `pattern=".{8,}"` — regex para mínimo 8 caracteres
- `checked` va en `<input>`, `selected` va en `<option>`
- `min="2026-05-22"` en `type="date"` evita fechas pasadas
- `step="10"` en `type="number"` solo permite múltiplos de 10
- `accept=".json,.yaml"` filtra archivos en el selector del SO — no es medida de seguridad