---
layout: "default"
title: "Mixins"
---

## Responsive

The responsive mixin works exactly like the bootstrap one, but is written slightly differently. 

- Uses viewport variables (`laptop`, `mobile`) instead of size variables (`lg`, `sm`)
- Has two parameters: `$value` and `$breakpoint`
  - value can be `up` or `down`
    - `up` will be applied when wider than the chosen breakpoint
    - `down` will be applied when narrower than the chosen breakpoint
  - breakpoint can be any of the [breakpoints variables]({% link _utils/variables.md %}) (without the `$` sign)

**Example**

```scss
.class {

  @include responsive(up, laptop) {
    // write styles here
  }

  @include responsive(down, mobile) {
    // write styles here
  }
}
```
