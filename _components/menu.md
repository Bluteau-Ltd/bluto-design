---
layout: "default"

label: "Navigation"
title: "Menu"
subtitle: "The menu component displays a list of linkm, on temporary or permanent surfaces. It can be used for anchor links, tabs or page links."
example: |-
  <div class="menu">
    <p class="menu__item menu__item--active">Who we are</p>
    <p class="menu__item">How we work</p>
    <p class="menu__item">Delivery zone</p>
    <p class="menu__item">Recurring order</p>
  </div>
---

## Elements

| Class | Description |
| --- | --- |
| `menu` | The main element |
| `menu__item` | The link element |

## Modifiers

Add classes to the base class `menu` to change the style of the component.

### Size

| Class | |
| --- | --- |
| `menu--sm` | Dense variant, used for the category filter on category pages |
| | Default size. No additional class is needed |
| `menu--lg` | Large variant, used for the settings page tabs (on v2 design) |

### Variant

| Class | |
| --- | --- |
| `menu--transparent` | Remove box-shadow and padding |
| `menu--noWrap` | Force `menu__item` elements text to be on a single line |

### States

These modifiers are applied to the `menu__item` element.

| Class | |
| --- | --- |
| `menu__item--active` | The active state. This is added conditionally with code |
| `menu__item--error` | Add a red color to the text and icons (used for logout link) |

## Examples

```html
<div class="menu">
  <p class="menu__item menu__item--active">Dashboard</p>
  <p class="menu__item">Order history</p>
  <p class="menu__item">Account settings</p>
  <p class="menu__item menu__item--error">Logout</p>
</div>
```

```html
<div class="menu menu--transparent">
  <p class="menu__item menu__item--active">All</p>
  <p class="menu__item">Bread</p>
  <p class="menu__item">Viennoiseries</p>
</div>
```
