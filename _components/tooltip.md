---
layout: "default"

label: "Feedback"
title: "Tooltip"
subtitle: "Add a tooltip to an element to give a bit of information."
example: |-
  <div class="tooltip">
    <p class="tag tag--lg tag--primary">Hover me</p>
    <span class="tooltip__content">This is a tooltip</span>
  </div>
---

Use with caution, as tooltips are not the most accessible components. They are tricky for keyboard users and do not display on touch devices.

## Elements

| Class | Description |
| --- | --- |
| `tooltip` | Element that will trigger the tooltip on hover (can be used on any DOM element, in addition to any other class anything) |
| `tooltip__content` | The tooltip text |

## Examples

```html
<div class="productIcon tooltip">
  <img src="" class="img-fluid productIcon__image" alt="Baguette">
  <span class="tooltip__content">Baguette</span>
</div>
```
