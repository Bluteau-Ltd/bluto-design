---
layout: "default"
title: "Text"
subtitle: "Description"
---

> Here be specific and talk about the difference betweem the styles classes and the modifiers, and the fact that modifiers apply to any element This is a special component in the sense that elements do not follow the BEM nomenclature (but modifiers does). Each elements has a disctinct class name.

## Elements

| Class | Size (in rem) | Default weight | Comment | Design |
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

| Classes | Comment |
| --- | --- |
| `text--underline` | Add a line below the text |
| `text--italic` |  |

### Weight

Overrides the font weigth (can be used on any element of the DOM).

| Classes |
| --- |
| `text--light` |
| `text--regular` |
| `text--bold` |

### Alignement

Change the text aligment (can be used on any element of the DOM).

| Classes |
| --- |
| `text--left` |
| `text--center` |
| `text--right` |

### Color

Change the text color (can be used on any element of the DOM).

| Classes |
| --- |
| `text--black` |
| `text--grey` |
| `text--white` |
| `text--main` |
| `text--blue` |
| `text--success` |
| `text--info` |
| `text--warning` |
| `text--error` |

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
