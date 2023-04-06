---
layout: "default"
title: "Button"
subtitle: "Component for every call-to-action."
---

## Elements

| Class | Comment |
| --- | --- |
| `button` | Main element |
| `button__wrapper` | Container of multiple buttons, handles spacing, alignement and responsive behaviour |
| `button__inner` | Only used for `button--menu` variant, creates the middle line of the menu icon |

## Modifiers

Add classes to the base class `button` to change the style of the component. There is also a modifier for `button__wrapper` element.

### Size

Override the default size of the component.

| Class | Comment | Design |
| --- | --- | --- |
| `button--xs` | | <a href="" class="button button--primary button--xs">Extra small</a> |
| `button--sm` | | <a href="" class="button button--primary button--sm">Small</a> |
| | The default size. No additional class is needed | <a href="" class="button button--primary">Medium</a> |
| `button--lg` | Larger button for when your CTA has to stand out. | <a href="" class="button button--primary button--lg">Large</a> |
| `button--xl` | Use very scarcely. Only used for very large CTAs on the public website | <a href="" class="button button--primary button--xl">Extra large</a> |

### Variant

Changes style depending on the button content.

| Class | Comment |
| --- | --- |
| | The default variant. You don't need to add an additional class | <a href="" class="button button--primary">Default</a> |
| `button--icon` | Icon only buttons | <a href="" class="button button--primary button--icon"></a> |
| `button--link` | Basic underlined links with no background color | <a href="" class="button--primary button--link">Link</a> |
| `button--transparent` | Remove the background color and use the color value as text (or icon) color | <a href="" class="button button--primary button--transparent">Transparent</a> |
| `button--menu` | Hamburger icon for mobile menu |
| `button--fullWidth` | Takes the full width of the container | <a href="" class="button button--primary button--fullWidth">Full width</a> |

### Color

Changes button color. Which element is colored (background, text, icon, etc.) will depend on the variant you use.

| Class | Design |
| --- | --- |
| `button--primary` | <a href="" class="button button--primary">Primary</a> |
| `button--secondary` | <a href="" class="button button--secondary">Secondary</a> |
| `button--highlight` | <a href="" class="button button--highlight">Highlight</a> |
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
<div class="button button--icon button--lg button--primary">
  @include('components.partials.svgs.icon-arrow-down')
</div>
```
