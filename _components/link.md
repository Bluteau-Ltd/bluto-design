---
layout: "default"

label: "Navigation"
title: "Link"
subtitle: "Simple underlined text link."
example: |-
  <div class="docs__link link link--primary">
    Link
    <img src="/assets/icons/chevron-right-primary.svg">
  </div>
---

## Elements

| Class | Description |
| - | - |
| `link` | Main element |

## Modifiers

Add classes to the base class `link` to change the style of the component.

### Color

Links will automatically inherit the color of their parent component. If you want to override that color, you can use the following class.

| Class | |
| - | - |
| `link--primary` | <span class="link link--primary">Primary</span> |

### Disabled



| Class | |
| - | - |
| `link--disabled` | <span class="link link--disabled">Disabled</span> |

## Examples

```html
<p class="body">
  Send us an email at 
  <a href="mailto:contact@bluto.co.uk" class="link">contact@bluto.co.uk</a>
</p>
```

```html
<a href="#" class="link link--primary">Go to section</a>
```

```html
<a href="#" class="link link--disabled">Log in</a>
```
