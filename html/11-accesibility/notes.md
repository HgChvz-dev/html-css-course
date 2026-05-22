# 11 — Accessibility

## Attributes learned

| Attribute            | Purpose                                                                 |
| -------------------- | ----------------------------------------------------------------------- |
| `aria-label`         | Descriptive label for screen readers — used when no visible text exists |
| `aria-labelledby`    | Links an element to its title by `id`                                   |
| `aria-describedby`   | Links an element to its description by `id`                             |
| `aria-hidden="true"` | Hides element from screen readers                                       |
| `aria-expanded`      | Indicates if an element is expanded or collapsed                        |
| `aria-live`          | Announces dynamic changes to screen readers                             |
| `aria-required`      | Marks a field as required for screen readers                            |
| `aria-invalid`       | Marks a field as having an error                                        |
| `role`               | Defines the semantic role of an element                                 |
| `tabindex`           | Controls keyboard navigation order                                      |

## Common roles

| Role                | Purpose                                 |
| ------------------- | --------------------------------------- |
| `role="button"`     | Element acts as a button                |
| `role="alert"`      | Important message announced immediately |
| `role="navigation"` | Navigation block                        |
| `role="main"`       | Main content                            |
| `role="banner"`     | Main page header                        |

## tabindex values

| Value           | Meaning                                                |
| --------------- | ------------------------------------------------------ |
| `tabindex="0"`  | Adds element to natural keyboard tab order             |
| `tabindex="-1"` | Removes element from tab order (focusable via JS only) |
| `tabindex="1+"` | NEVER use — breaks natural tab order                   |

## aria-live values

| Value       | Meaning                                     |
| ----------- | ------------------------------------------- |
| `polite`    | Announces when user is idle — non-urgent    |
| `assertive` | Announces immediately — for critical alerts |

## Rules learned

- Never use `tabindex` with positive values — always `0` or `-1`
- `aria-label` is for elements without visible text (icon buttons)
- `aria-labelledby` points to an existing visible title by `id`
- `aria-hidden="true"` on decorative icons prevents redundant announcements
- `role="alert"` is announced immediately — use only for errors
- `role="button"` on a `<div>` also needs `tabindex="0"` to be keyboard accessible
- Semantic HTML first — use ARIA only when HTML alone isn't enough

---

# 11 — Accesibilidad

## Atributos aprendidos

| Atributo             | Para qué sirve                                                               |
| -------------------- | ---------------------------------------------------------------------------- |
| `aria-label`         | Etiqueta descriptiva para lectores de pantalla — cuando no hay texto visible |
| `aria-labelledby`    | Vincula un elemento con su título por `id`                                   |
| `aria-describedby`   | Vincula un elemento con su descripción por `id`                              |
| `aria-hidden="true"` | Oculta el elemento a lectores de pantalla                                    |
| `aria-expanded`      | Indica si un elemento está expandido o colapsado                             |
| `aria-live`          | Anuncia cambios dinámicos a lectores de pantalla                             |
| `aria-required`      | Marca un campo como obligatorio para lectores de pantalla                    |
| `aria-invalid`       | Marca un campo como con error                                                |
| `role`               | Define el rol semántico de un elemento                                       |
| `tabindex`           | Controla el orden de navegación con teclado                                  |

## Roles comunes

| Rol                 | Para qué sirve                           |
| ------------------- | ---------------------------------------- |
| `role="button"`     | El elemento actúa como botón             |
| `role="alert"`      | Mensaje importante anunciado al instante |
| `role="navigation"` | Bloque de navegación                     |
| `role="main"`       | Contenido principal                      |
| `role="banner"`     | Header principal de la página            |

## Valores de tabindex

| Valor           | Significado                                                    |
| --------------- | -------------------------------------------------------------- |
| `tabindex="0"`  | Agrega el elemento al orden natural de teclado                 |
| `tabindex="-1"` | Quita el elemento del orden de teclado (enfocable solo con JS) |
| `tabindex="1+"` | NUNCA usar — rompe el orden natural de teclado                 |

## Valores de aria-live

| Valor       | Significado                                          |
| ----------- | ---------------------------------------------------- |
| `polite`    | Anuncia cuando el usuario está inactivo — no urgente |
| `assertive` | Anuncia inmediatamente — para alertas críticas       |

## Reglas aprendidas

- Nunca usar `tabindex` con valores positivos — siempre `0` o `-1`
- `aria-label` es para elementos sin texto visible (botones de icono)
- `aria-labelledby` apunta a un título visible existente por `id`
- `aria-hidden="true"` en iconos decorativos evita anuncios redundantes
- `role="alert"` se anuncia inmediatamente — solo para errores
- `role="button"` en un `<div>` también necesita `tabindex="0"` para ser accesible con teclado
- HTML semántico primero — usar ARIA solo cuando el HTML solo no es suficiente