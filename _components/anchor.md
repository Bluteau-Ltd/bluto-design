---
layout: "default"

label: "Navigation"
title: "Anchor"
subtitle: "Create a dynamic scroll to another part of the same page with an anchor link."
example: |-
  <div class="docs__anchors anchors">
    <div class="anchor__wrapper"><a class="anchor" href="#elements">Elements</a></div>
    <div class="anchor__wrapper"><a class="anchor" href="#examples">Examples</a></div>
  </div>
---

## Elements

Like buttons or tabs, this component has two blocks: `anchor` and `anchors`. The former is the single component, the latter the wrapper for multiple instances of the component.

| Class | Description |
| --- | --- |
| `anchors` | Wrapper for multiple elements |
| `anchor` | Main element |
| `anchor__wrapper` | Capsule around the main element for spacing consistency and responsive behaviour |
| `anchor__target` | Optionnal. Use this class on the targetted element to add fake space above it so that it doesn't scroll past the navbar |

> `anchor__target` is usually outside of the DOM structure of the `anchors` block.

## Examples

```html
<div class="anchors">
  <div class="anchor__wrapper">
    <a href="#" class="anchor"></a>
  </div>
  <div class="anchor__wrapper">
    <a href="#section-1" class="anchor"></a>
  </div>
</div>

<div id="section-1" class="section">
  <!-- add content -->
</div>

<div id="section-2" class="section">
  <!-- add content -->
</div>
```
