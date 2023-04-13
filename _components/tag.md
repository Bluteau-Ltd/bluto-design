---
layout: "default"

label: "Data"
title: "Tag"
subtitle: "Tags are small snippets of short text giving information about the elements they are associated with (usually their state)."
---

## Elements

Like buttons or tabs, this component has two blocks: `tag` and `tags`. The former is the single component, the latter the wrapper for multiple instances of the component.

| Class | Description |
| --- | --- |
| `tags` | Wrapper for multiple elements |
| `tag` | Main element |

## Modifiers

Add classes to the base class `tag` to change the style of the component. There is also a modifier for the `tags` block.

### Size

Override the default size of the component.

| Class | |
| --- | --- |
| `tag--sm` | <span class="tag tag--sm tag--primary">Small</span> |
| | <span class="tag tag--primary">Medium (default)</span> |
| `tag--lg` | <span class="tag tag--lg tag--primary">Large</span> |

### Color

Change the tag color.

| Class | |
| --- | --- |
| `tag--primary` | <span class="tag tag--primary">Primary</span> |
| `tag--secondary` | <span class="tag tag--secondary">Secondary</span> |
| `tag--success` | <span class="tag tag--success">Success</span> |
| `tag--info` | <span class="tag tag--info">Info</span> |
| `tag--warning` | <span class="tag tag--warning">Warning</span> |
| `tag--error` | <span class="tag tag--error">Error</span> |

### Direction

For `tags` element. Changes the stacking direction.

| Class | |
| --- | --- |
| `tags--portrait` | Display the tags vertically |

## Examples

```html
<div class="tags">
  <p class="tag tag--sm tag--success"></p>
  <p class="tag tag--sm tag--error"></p>
</div>
```

```html
<div class="tags tags--portrait">
  <p class="tag tag--primary"></p>
  <p class="tag tag--secondary"></p>
  <p class="tag tag--success"></p>
</div>
```
