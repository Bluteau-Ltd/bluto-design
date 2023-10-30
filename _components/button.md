---
layout: "default"

label: "Navigation"
title: "Button"
subtitle: "Component for every call-to-action."
example: |-
  <div class="button__wrapper">
    <div class="button button--md button--primary">Sign up</div>
    <div class="button button--md button--secondary">Login</div>
    <div class="button button--md button--grey">Next</div>
  </div>
---

## Elements

Like anchors or tabs, this component has two blocks: `button` and `buttons`. The former is the single component, the latter the wrapper for multiple instances of the component.

| Class | Description |
| --- | --- |
| `buttons` | Container of multiple buttons, handles spacing, alignement and responsive behaviour |
| `button` | Main element |

## Modifiers

Add classes to the base class `button` to change the style of the component. There is also a modifier for `button__wrapper` element.

### Size

Override the default size of the component.

| Class | Description | Design |
| --- | --- | --- |
| `button--xs` | | <a href="" class="button button--primary button--xs">Extra small</a> |
| `button--sm` | | <a href="" class="button button--primary button--sm">Small</a> |
| | The default size. No additional class is needed | <a href="" class="button button--primary">Medium</a> |
| `button--lg` | Larger button for when your CTA has to stand out. | <a href="" class="button button--primary button--lg">Large</a> |
| `button--xl` | Use very scarcely. Only used for very large CTAs on the public website | <a href="" class="button button--primary button--xl">Extra large</a> |

### Variant

Changes style depending on the button content.

| Class | Description |
| --- | --- |
| | The default variant. You don't need to add an additional class | <a href="" class="button button--primary">Default</a> |
| `button--icon` | Icon only button | <a href="" class="button button--primary button--icon"><img src="/assets/icons/chevron-down-white.svg"></a> |
| `button--transparent` | Remove the background color and padding and use the color modifier for text (or icon) color | <a href="" class="button button--primary button--transparent">Transparent</a> |
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

### Direction

Only applies to the `buttons` block.

| Class | Design |
| --- | --- |
| `buttons--portrait` | Overrides the default stacking of buttons |

### Wrap

Only applies to the `buttons` block.

| Class | Design |
| --- | --- |
| `buttons--wrap` | Set buttons on multiple lines if the block is wider than the parent container width |

## Examples

```html
<div class="buttons">
  <a href="" class="button button--md button--error">Cancel</a>
  <div class="buttons">
    <a href="" class="button button--md button--grey">Skip</a>
    <a href="" class="button button--md button--secondary disabled">Next</a>
  </div>
</div>
```

```html
<a href="" class="button button--icon button--lg button--primary">
  <!-- include icon in svg format (import from package or blade component) -->
</a>
```
