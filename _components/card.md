---
layout: "default"

label: "Layout"
title: "Card"
subtitle: "Cards are surfaces that display content and actions for a single element. They are one of the most used layout elements."
example: |-
  <div class="docs__card card">
    <div class="card__header">
      <h3 class="card__title">Tradition baguette</h3>
      <p class="card__subtitle">The reason why we wake up every morning</p>
    </div>
    <div class="card__content">
      <p class="body">Perfect with every meal, from breakfast to dinner. For us, the best is to mop up the juice or the sauce at the end of your meal!</p>
    </div>
    <div class="card__actions">
      <div>
        <button class="button button--error"></button>
        <button class="button button--grey"></button>
      </div>
      <button class="button button--secondary"></button>
    </div>
  </div>
---

## Elements

| Class | Description |
| --- | --- |
| `card` | Main element |
| `card__image` | |
| `card__header` | Card title, usually made of a `card__title` and `card__subtitle` elements |
| `card__title` | You don't need to specify a text style, it is added automatically  |
| `card__subtitle` | Optional. Display a smaller text below the title. You don't need to specify a text style, it is added automatically |
| `card__content` | Cards can have multiple instances of that element |
| `card__actions` | Optional. Always the last element of the card, displays the buttons. Can have one or two children. If you have more than three buttons, wrap the ones to display together in a div |

> In order for the styling to work, the children elements **image**, **header**, **content** and **actions** have to be siblings.

## Modifiers

Add classes to the base class `card` to change the style of the component.

### Size

Overrides the default size of the card. This changes:

- the card `border-radius`
- the childre elements `padding`
- the `card__title` and `card__subtitle` text sizes

| Classes |
| --- |
| `card--sm` |
| `card--lg` |

### Variants

Changes the overral style of the card.

| Classes | Description |
| --- | --- |
| `card--center` | Centers all the content of the card |
| `card--no-shadow` | Removes the background shadow |
| `card--transparent` | Removes the background shadow and the outer padding |
| `card--mobile` | Removes the background shadow and the outer padding on mobile devices (see login page) |

## Overrides

If you need to apply some styling to a specific instance of the card component (i.e. `card--product`, `card--ingredients`), you can create a custom modifier and add your styles in that section.

## Examples

```html
<div class="card card--sm card--transparent">
  <div class="card__header">
    <h3 class="card__title"></h3>
    <p class="card__subtitle"></p>
  </div>
  <div class="card__content">
    <!-- add content -->
  </div>
  <div class="card__content">
    <!-- add content -->
  </div>
  <div class="card__actions">
    <div>
      <button class="button button--error"></button>
      <button class="button button--grey"></button>
    </div>
    <button class="button button--secondary"></button>
  </div>
</div>
```
