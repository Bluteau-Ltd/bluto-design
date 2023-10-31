---
layout: "default"

label: "Navigation"
title: "Link"
subtitle: "Simple underlined text link."
example: |-
  <div class="docs__link link link--primary">
    Link
    <svg width="24" height="24" viewBox="0 0 24 24" fill="#D29132" xmlns="http://www.w3.org/2000/svg">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M8.29289 5.29289C8.68342 4.90237 9.31658 4.90237 9.70711 5.29289L15.7071 11.2929C16.0976 11.6834 16.0976 12.3166 15.7071 12.7071L9.70711 18.7071C9.31658 19.0976 8.68342 19.0976 8.29289 18.7071C7.90237 18.3166 7.90237 17.6834 8.29289 17.2929L13.5858 12L8.29289 6.70711C7.90237 6.31658 7.90237 5.68342 8.29289 5.29289Z"/>
    </svg>
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
