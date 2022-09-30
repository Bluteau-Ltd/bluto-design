---
layout: "default"
title: "Button"
subtitle: "Component for every call-to-action."
---

## Modifiers

Add classes to the base class `button` to change the style of the component.

### Size

Override the default size of the compoent.

| Class | Comment | Design |
| --- | --- | --- |
| `button--xs` | | <a href="" class="button button--main button--xs">Extra small</a> |
| `button--sm` | | <a href="" class="button button--main button--sm">Small</a> |
| | The default size. You don't need to add an additional class | <a href="" class="button button--main">Medium</a> |
| `button--lg` | Use very scarcely. Only used for very large CTAs on the public website | <a href="" class="button button--main button--lg">Large</a> |

### Variant

Changes style depending on the button content.

| Class | Comment |
| --- | --- |
| | The default size. You don't need to add an additional class | <a href="" class="button button--main">Default</a> |
| `button--icon` | Icon only buttons | <a href="" class="button button--main button--icon"></a> |
| `button--link` | Basic underlined links with no background color | <a href="" class="button--main button--link">Link</a> |
| `button--transparent` | Remove the background color and use the color value as text (or icon) color | <a href="" class="button button--main button--transparent">Transparent</a> |
| `button--fullWidth` | Takes the full width of the container | <a href="" class="button button--main button--fullWidth">Full width</a> |

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

## Examples

```html
<div class="button button--sm button--error">
  Label
</div>
```

```html
<div class="button button--icon button--lg button--main">
  @include('components.partials.svgs.icon-arrow-down')
</div>
```
