---
layout: "default"

label: "Navigation"
title: "Accordion"
subtitle: "A collection of collapsible elements."
example: |-
  <div class="docs__accordion accordion" data-module="collapse">
    <div class="js-collapse accordion__item">
      <p class="js-collapse-button accordion__header">Where do you deliver?</p>
      <div class="js-collapse-content accordion__content">We operate in the following postcodes: <strong>W8, W9, W10, W11, W12, W14</strong></div>
    </div>
    <div class="js-collapse accordion__item">
      <p class="js-collapse-button accordion__header">When do you deliver?</p>
      <div class="js-collapse-content accordion__content">Here are our opening times: <strong>06:00–13:00</strong></div>
    </div>
  </div>
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
