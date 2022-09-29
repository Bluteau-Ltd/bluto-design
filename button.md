---
layout: "default"
title: "Button"
subtitle: "Component for every call-to-action."
---

### Modifiers

### Size

Override the default size of the compoent.

| Class | Description |
| --- | --- |
| `button--xs` | <a href="" class="button button--main">Primary</a> |
| `button--sm` | |
| `button--lg` | Use very scarcely. Only used for very large CTAs on the public website |

### Variant

Changes style depending on the button content.

| Class | Description |
| --- | --- |
| `button--icon` | Icon only buttons |
| `button--link` | Basic underlined links with no background color |
| `button--transparent` | Remove the background color and use the color value as text (or icon) color |
| `button--menu` | Hamburger icon for mobile menu |
| `button--fullWidth` | Takes the full width of the container |

### Color

Changes button color. Which element is colored (background, text, icon, etc.) will depend on the variant you use.

| Class | Design |
| --- | --- |
| `button--main` | <a href="" class="button button--main">Main</a> |
| `button--blue` | <a href="" class="button button--blue">Blue</a> |
| `button--yellow` | <a href="" class="button button--yellow">Yellow</a> |
| `button--success` | <a href="" class="button button--success">Success</a> |
| `button--info` | <a href="" class="button button--info">Info</a> |
| `button--warning` | <a href="" class="button button--warning">Warning</a> |
| `button--error` | <a href="" class="button button--error">Error</a> |
| `button--white` | <a href="" class="button button--white">White</a> |
| `button--grey` | <a href="" class="button button--grey">Grey</a> |
| `button--black` | <a href="" class="button button--black">Black</a> |
| `button--instagram` | <a href="" class="button button--instagram">Instagram</a> |
| `button--facebook` | <a href="" class="button button--facebook">Facebook</a> |

### Example

```html
<div class="button button--sm button--error">
  Label
</div>

<div class="button button--icon button--main">
  @include('components.partials.svgs.icon-arrow-down')
</div>
```
