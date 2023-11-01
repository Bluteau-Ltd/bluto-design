---
layout: "default"

label: "Mixins"
title: "Text"
subtitle: "For this component, elements do not follow the BEM nomenclature (but modifiers do). Elements all have unique classes names, each class name corresponding to a different text style. Modifiers can be applied to any element, not necessarily text."
example: |-
  <div class="text--right">
      <p class="body">
        <span class="h2">To write</span>
        <span class="h6">rich</span>
        <span class="caption">yet consistent</span>
      </p>
      <p class="body">
        <span class="text--strikeThrough">texts</span>
        <span class="text--italic">you have</span>
        <span class="text--bold">to</span>
        <span class="subtitle">create</span>
      </p>
      <p class="body">
        <span class="h4 text--underline">a robust style guide</span>
      </p>
  </div>
---

## Elements

| Class | Size (in rem) | Default weight | Description | Design |
| --- | --- |--- | --- | --- |
| `h1` | 3.5 | bold | Home page title | <span class="h1">h1</span>
| `h2` | 2.5 | bold | Default page titles | <span class="h2">h2</span>
| `h3` | 2 | bold | Section titles | <span class="h3">h3</span>
| `h4` | 1.75 | bold | Large card titles | <span class="h4">h4</span>
| `h5` | 1.5 | bold | Default card title | <span class="h5">h5</span>
| `h6` | 1.25 | bold | Small card titles | <span class="h6">h6</span>
| `subtitle` | 1.125 | regular | Larger body text, used for lead text and page subtitles | <span class="subtitle">subtitle</span>
| `body` | 1 | regular | Default body text | <span class="body">body</span>
| `caption` | 0.875 | bold | Smaller body text, used for labels or legends | <span class="caption">caption</span>
| `overline` | 0.75 | regular | Smallest body text, use scarcely | <span class="overline">overline</span>

> For headings, the style value has nothing to do with the DOM component you are using. A h1 tag can have a h2 class.

> All font sizes are given in rem units. The default font size is 16px.

## Modifiers

### Style

Overrides the font style (can be used on any element of the DOM).

| Classes | |
| --- | --- |
| `text--underline` | <span class="text--underline">Add a line below the text</span> |
| `text--italic` | <span class="text--italic">Slant the text</span> |
| `text--strikeThrough` | <span class="text--strikeThrough">Add a line through the text</span> |

### Weight

Overrides the font weigth (can be used on any element of the DOM).

| Classes | |
| --- | --- |
| `text--light` | <span class="text--light">Text with a light weight</span> |
| `text--regular` | <span class="text--regular">Text with a regular weight (default)</span> |
| `text--bold` | <span class="text--bold">Text with a bold weight</span> |

### Alignement

Change the text aligment (can be used on any element of the DOM).

| Classes |
| --- |
| `text--left` | <span style="display: block;" class="text--left">Left text</span> |
| `text--center` | <span style="display: block;" class="text--center">Centered text</span> |
| `text--right` | <span style="display: block;" class="text--right">Right text</span> |

### Color

Change the text color (can be used on any element of the DOM).

| Classes |
| --- |
| `text--default` | <span class="body text--default">This is a default text</span> |
| `text--alt` | <span class="body text--alt">This is an alternate text</span> |
| `text--disabled` | <span class="body text--disabled">This is a disabled text</span> |
| `text--contrast` | <span class="docs__textBlock fill--black"><span class="body text--contrast">This is a default contrast text</span></span> |
| `text--contrastAlt` | <span class="docs__textBlock fill--black"><span class="body text--contrastAlt">This is an alternate contrast text</span></span> |
| `text--contrastDisabled` | <span class="docs__textBlock fill--black"><span class="body text--contrastDisabled">This is a disabled contrast text</span></span> |
| `text--primary` | <span class="body text--primary">This is a primary text</span> |
| `text--secondary` | <span class="body text--secondary">This is a secondary text</span> |
| `text--success` | <span class="body text--success">This is a success text</span> |
| `text--info` | <span class="body text--info">This is an info text</span> |
| `text--warning` | <span class="body text--warning">This is a warning text</span> |
| `text--error` | <span class="body text--error">This is an error text</span> |

## Examples

```html
<h1 class="h2"></h1>
```

```html
<p class="subtitle text--grey"></p>
```

```html
<div class="text--center">
  <p class="caption"></p>
  <p class="body text--bold"></p>
</div>
```
