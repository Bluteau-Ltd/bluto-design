---
layout: "default"
title: "Accordion"
subtitle: "A collection of collapsible elements."
---

## Elements

| Class | Description |
| --- | --- |
| `accordion__item` | Collapsible component, composed of a header (the trigger) and some content |
| `accordion__header` | Trigger element, containing some text. The expand/collapse icon is added automatically |
| `accordion__content` | What is displayed when the accordion is expanded |

## Modifiers

Add classes to the base class `accordion` to change the style of the component. There is also a modifier for the `accordion__item` element.

### Size

When accordions are displayed in small block, you can use a dense variant of the componant.

| Class | Desscription |
| --- | --- |
| `accordion--sm` | Makes all the elements smaller |

### Active

If you want one of the items to be expanded by default you can add a class to the `accordion__item` element.

| Class | Desscription |
| --- | --- |
| `is-active` | Expands by default an `accordion__item` |

## Example

```html
<div class="accordion">
  <div class="accordion__item">
    <p class="accordion__header"></p>
    <div class="accordion__content"></div>
  </div>
  <div class="accordion__item">
    <p class="accordion__header"></p>
    <div class="accordion__content"></div>
  </div>
</div>
```