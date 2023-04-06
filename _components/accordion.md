---
layout: "default"
title: "Accordion"
subtitle: "A collection of collapsible elements."
---

## Elements

| Class | Description |
| --- | --- |
| `accordion__item` | collapsible component, composed of a header (the trigger) and some content |
| `accordion__header` | trigger element, containing some text. it adds the trigger icon automatically |
| `accordion__content` | What is displayed when the accordion is expanded |

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
