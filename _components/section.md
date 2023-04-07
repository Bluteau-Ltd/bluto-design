---
layout: "default"

label: "Layout"
title: "Section"
subtitle: "Main layout component. Each page is a succession of section with different modifiers"
---

## Elements

| Class | Description |
| --- | --- |
| `section` | Main element |
| `section__container` | Required. Sets the max-width of the section content |
| `section__header` | Optional. Header of the section, composed mainly of a title and a subtitle |
| `section__label` | Can only be used inside `section__header` |
| `section__title` | Can only be used inside `section__header` |
| `section__subtitle` | Can only be used inside `section__header` |
| `section__content` |  |
| `section__divider` | Adds a wave divider at the top or bottom of the section |

## Modifiers

### Color

Sets the background color of the section. The default value is white. This automatically changes the color of coloured elements such as titles, input border color, etc.

| Classes |
| --- |
| `section--white` | <span class="colorBlock fill--white"></span> |
| `section--primary` | <span class="colorBlock fill--main"></span> |
| `section--secondary` | <span class="colorBlock fill--secondary"></span> |
| `section--secondaryLighter` | <span class="colorBlock fill--secondaryLighter"></span> |

### Variants

| Classes | Description |
| --- | --- |
| `section--fullWidth` | Display the section__content element on the full width of the page (e.g. [product carousel](https://www.bluto.co.uk/#products-carousel)) |

## Examples

```html
<div class="section">
  <div class="section__container">
    <div class="section__header">
      <div class="section__title"></div>
      <div class="section__subtitle"></div>
    </div>
    <div class="section__content"></div>
  </div>
</div>
```
