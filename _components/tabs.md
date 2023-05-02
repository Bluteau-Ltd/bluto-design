---
layout: "default"

label: "Navigation"
title: "Tabs"
subtitle: "Tabs are a way to divide content on mutliple sections on the same page and navigate between them."
example: |-
  <div>
  </div>
---

## Elements

Like buttons or anchors, this component has two blocks: `tab` and `tabs`. The former is the single component, the latter the wrapper for multiple instances of the component.

> This only creates the style of the component, and is not used for javascript functionnality.

| Class | Description |
| --- | --- |
| `tabs` | Wrapper for multiple elements |
| `tab` | Main element |
| `tab__wrapper` | Capsule around the main element for spacing consistency and responsive behaviour |
| `tab__target` | Use this class on the targetted element to control visibility |

> `tab__target` is usually outside of the DOM structure of the `tabs` block.

## Modifiers

Add classes to the base class `tabs` to change the style of the wrapper.

### Size

When tabs are displayed in small block, you can use a dense variant of the componant.

| Class | |
| --- | --- |
| `tabs--sm` | Makes all the tab elements smaller |

## Examples

```html
<div class="section">
  <ul class="tabs nav" role="tablist">
    <li class="tab__wrapper" role="presentation">
      <a class="tab active" id="tab-2'" data-toggle="tab" href="#tab-2" role="tab">Tab 1</a>
    </li>
    <li class="tab__wrapper" role="presentation">
      <a class="tab" id="tab-2'" data-toggle="tab" href="#tab-2" role="tab">Tab 1</a>
    </li>
    <li class="tab__wrapper" role="presentation">
      <a class="tab" id="tab-2'" data-toggle="tab" href="#tab-2" role="tab">Tab 1</a>
    </li>
  </ul>
</div>

<div class="section">
  <div class="tabs__target active" id="tab-1" role="tabpanel">
    <!-- add content -->
  </div>
  <div class="tabs__target" id="tab-2" role="tabpanel">
    <!-- add content -->
  </div>
  <div class="tabs__target" id="tab-3" role="tabpanel">
    <!-- add content -->
  </div>
</div>
```
