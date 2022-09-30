---
layout: "default"
title: "Alert"
subtitle: "An alert (or snackbar, toast message, etc.) component. Used to display feedback to the user after an action, but also to emphasise an element on a page (for a notice for intance)."
---

> The icon on the left is added automatically with CSS.

## Elements

| Class | Description |
| --- | --- |
| `alert__title` | Main text of the alert |
| `alert__subtitle` | Optional. Smaller text below the title |
| `alert__close` | Close icon (only used for toast messages) |

## Modifiers

Add classes to the base class `alert` to change the style of the component.

### Color

Changes the alert color to convey the severity of the alert.

| Class | Design |
| --- | --- |
| `alert--success` | <span class="alert alert--success alert--notice"></span> |
| `alert--info` | <span class="alert alert--info alert--notice"></span> |
| `alert--warning` | <span class="alert alert--warning alert--notice"></span> |
| `alert--error` | <span class="alert alert--error alert--notice"></span> |

### Wariant

| Class | Description |
| --- | --- |
| `alert--notice` | Overrides the default absolute positioning to display the alert as a notice on the page |

### size

Overrides the font size and paddings of the alert component.

| Class | Description |
| --- | --- |
| `alert--sm` | Makes the alert component smaller (eg. if it's used for a form notice) |

## Example

```html
<div class="alert alert--success">
  <p class="alert__title"></p>
  <p class="alert__subtitle"></p>
  <button type="button" class="alert__close"></button>
</div>
```

```html
<div class="alert alert--info alert--notice">
  <p class="alert__title"></p>
</div>
```