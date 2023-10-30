---
layout: "default"

label: "Layout"
title: "Grid"
subtitle: "Layout component to create column based grid structure like bootstrap."
example: |-
  <div class="docs__grid grid grid--spacing1 grid--column">
    <div class="grid__item"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
    <div class="grid grid--spacing1 grid--jc-start grid__item">
      <div class="grid__item grid__item--4"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
      <div class="grid__item grid__item--2"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
      <div class="grid__item grid__item--6"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
    </div>
    <div class="grid grid--spacing1 grid--jc-start grid__item">
      <div class="grid__item grid__item--4"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
      <div class="grid__item grid__item--8"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
    </div>
    <div class="grid grid--spacing1 grid--jc-start grid__item">
      <div class="grid__item grid__item--3"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
      <div class="grid__item grid__item--3"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
      <div class="grid__item grid__item--3"><div class="fill--grey40" style="border-radius: 8px; padding: 8px;"></div></div>
    </div>
  </div>
---

- Based on a 12 column grid
- Use the flexbox properties
- Has two elements: the `grid` parent block and the `grid__item` child element. 
- The parent and child should **always follow each other directly**.
- A `grid__item` can also be a `grid` if it's a parent of `grid__item` elements.

## Elements

| Class | Description |
| --- | --- |
| `grid` | Parent element |
| `grid__item` | Child element |

> This comopenent has a specificity: some modifiers can be aplied to both the block `grid` and the element `grid__item`

## Modifiers

### Variants

Can only be applied to `grid`.

| Classes | Description |
| --- | --- |
| `grid--container` | Add a bigger top margin betweem two `grid` blocks |

### Spacing

Sets the spacing between `grid__item` elements. Can only be applied to `grid`.

| Classes | Description |
| --- | --- |
| `grid--spacingX` | X can be a value between 1 to 12, one being the [`$spacing`]({% link _utils/variables.md %}#spacing) variable, and the rest a multiple of that variable |

### Width

Sets the width of `grid__item` elements. Can only be applied to `grid__item`.

| Classes | Description |
| --- | --- |
| `grid__item--X` | X can be a value between 1 to 12 |
| `grid__item--smX` | Column width applied if wider than the `$mobile` breakpoint |
| `grid__item--mdX` | Column width applied if wider than the `$tablet` breakpoint |
| `grid__item--lgX` | Column width applied if wider than the `$laptop` breakpoint |
| `grid__item--xlX` | Column width applied if wider than the `$desktop` breakpoint |

### Direction

Overrides the `flex-direction` value. Can be applied to both `grid` and `grid__item`.

| Classes |
| --- |
| `grid--column` |
| `grid--column-reverse` |
| `grid--row` |
| `grid--row-reverse` |

### Justify content

Overrides the `justify-content` value. Can be applied to both `grid` and `grid__item`.

| Classes |
| --- |
| `grid--jc-center` |
| `grid--jc-end` |
| `grid--jc-start` |
| `grid--jc-space-around` |
| `grid--jc-space-between` |
| `grid--jc-space-evenly` |

### Align items

Overrides the `align-items` value. Can be applied to both `grid` and `grid__item`.

| Classes |
| --- |
| `grid--ai-center` |
| `grid--ai-end` |
| `grid--ai-start` |
| `grid--ai-stretch` |
| `grid--ai-baseline` |

## Example

```html
<div class="grid grid--spacing4">
  <div class="grid__item grid__item--lg7 grid__item--md6"></div>
  <div class="grid grid--spacing1 grid__item grid__item--lg3 grid__item--md6">
    <div class="grid__item grid__item--4"></div>
    <div class="grid__item grid__item--4"></div>
    <div class="grid__item grid__item--2"></div>
  </div>
</div>
```
