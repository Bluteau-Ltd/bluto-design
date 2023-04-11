---
layout: "default"

title: "File structure"
subtitle: "Every component file follows the same structure, related to BEM terminology, to make it understansable at first glance."
---

```scss
// ——————————————————————————————————————————————————
// reset
// elements
// modifier 1 (e.g. color)
// modifier 2 (e.g. position)
// modifier 3 (e.g. proportion)
// etc...
// overrides
// views
// ——————————————————————————————————————————————————
```

| Section | Description |
| --- | --- |
| reset | Optional. Additional reset styles associated with a component. |
| elements | Style of the block and all the elements |
| modifier | Styles associated with a specific modifier |
| overrides | Versions of the component used for a specific purpose (eg. `card--products`, `accordion--faq`) |
| views | Overriding styles associated with a specific view or instance of the component on the website |

### Example

```scss
// ——————————————————————————————————————————————————
// elements
// color
// variant
// size
// views
// ——————————————————————————————————————————————————

// ——————————————————————————————————————————————————
// elements
// ——————————————————————————————————————————————————

.alert {
  // add properties

  &__title {
    // add properties
  }

  &__subtitle {
    // add properties
  }

  &__close {
    // add properties
  }
}

// ——————————————————————————————————————————————————
// color
// ——————————————————————————————————————————————————

@mixin color() {
  // add properties
}

.alert {

  &--success { @include color(success); }
  &--info { @include color(info); }
  &--warning { @include color(warning); }
  &--error { @include color(error); }
}

// ——————————————————————————————————————————————————
// variant
// ——————————————————————————————————————————————————

.alert {
  
  &--notice {
    // add properties
  }
}

// ——————————————————————————————————————————————————
// size
// ——————————————————————————————————————————————————

.alert--sm {
  // add properties

  &.alert--notice {
    // add properties
  }

  .alert__title {
    // add properties
  }
}

// ——————————————————————————————————————————————————
// views
// ——————————————————————————————————————————————————

#page-contact {

  .alert {
    // add properties
  }
}
```
