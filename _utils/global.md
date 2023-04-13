---
layout: "default"

title: "Global classes"
subtitle: "A bit like Tailwind CSS, you can use classes to apply properties to an element. This can be useful when creating a custom class is a bit too much."
---

Like the rest of the framework, it uses some sort of [BEM]({% link _documentation/conventions.md %}#bem-markdown) terminology: the property (first word of the class) is the block, and the second word is the modifier.

## Responsive

Hide and show elements depending on viewport width or device type.

| Class | Description |
| --- | --- |
| `show-desktop` | Show elements if viewport is wider than `1280px` |
| `show-laptop` | Show elements if viewport is wider than `1024px` |
| `show-tablet` | Show elements if viewport is wider than `768px` |
| `show-mobile` | Show elements if viewport is wider than `568px` |
| `show-mobileSm` | Show elements if viewport is wider than `350px` |
| `show-touch` | Show elements on touch devices |

| Class | Description |
| --- | --- |
| `hide-desktop` | Hide elements if viewport is wider than `1280px` |
| `hide-laptop` | Hide elements if viewport is wider than `1024px` |
| `hide-tablet` | Hide elements if viewport is wider than `768px` |
| `hide-mobile` | Hide elements if viewport is wider than `568px` |
| `hide-mobileSm` | Hide elements if viewport is wider than `350px` |
| `hide-touch` | Hide elements on touch devices |

## Spacing and size

### Margin and padding

Add a custom margin or padding to an element. 

- The first letter specifies margin (`m`) or padding (`p`)
- The second letter (if any) the direction.
- The number modifier is a multiple of the [`$int`]({% link _utils/variables.md %}#spacing) variable. 

| Class | Description |
| --- | --- |
| `m-05` | Add a margin around the element of half the `$int` variable |
| `m-X` | Add a margin around the element (X can be a value between 1 to 20) |
| `mt-05` | Add a top margin of half the `$int` variable |
| `mt-X` | Add a top margin (X can be a value between 1 to 20) |
| `mr-05` | Add a right margin of half the `$int` variable |
| `mr-X` | Add a right margin (X can be a value between 1 to 20) |
| `mb-05` | Add a bottom margin of half the `$int` variable |
| `mb-X` | Add a bottom margin (X can be a value between 1 to 20) |
| `ml-05` | Add a left margin of half the `$int` variable |
| `ml-X` | Add a left margin (X can be a value between 1 to 20) |

| Class | Description |
| --- | --- |
| `p-05` | Add a margin around the element of half the `$int` variable |
| `p-X` | Add a margin around the element (X can be a value between 1 to 20) |
| `pt-05` | Add a top margin of half the `$int` variable |
| `pt-X` | Add a top margin (X can be a value between 1 to 20) |
| `pr-05` | Add a right margin of half the `$int` variable |
| `pr-X` | Add a right margin (X can be a value between 1 to 20) |
| `pb-05` | Add a bottom margin of half the `$int` variable |
| `pb-X` | Add a bottom margin (X can be a value between 1 to 20) |
| `pl-05` | Add a left margin of half the `$int` variable |
| `pl-X` | Add a left margin (X can be a value between 1 to 20) |

### Width

| Class | Description |
| --- | --- |
| `w-X` | Set a custom width, in percentage of the container, to an element (increment of 5) |

## Position

Overrides the position propery of an element. We use three letters for this one, to not mistake it with the padding classes.

| Class | Description |
| --- | --- |
| `pos-sticky` | Add position sticky to the element (with a global top offset for consistency) |

## Display

### General display

Override the display propery of an element.

| Class | Description |
| --- | --- |
| `d-flex` | Add `display: flex` property |
| `d-inlineFlex` | Add `display: inline-flex` property |
| `d-block` | Add `display: block` property |
| `d-inlineBlock` | Add `display: inline-block` property |

### Flexbox

This framework used mainly flexbox for positionning elements (see [Grid]({% link _components/grid.md %}) component). If your element has a `flex` or `inline-flex` property applied, you can use the following classes to override flexbox properties.

#### Flex-grow

| Class | Description |
| --- | --- |
| `fg-0` | Add `flex-grow: 0` property |
| `fg-1` | Add `flex-grow: 1` property |

#### Flex-basis

| Class | Description |
| --- | --- |
| `fb-0` | Add `flex-basis: 0` property |
| `fb-1` | Add `flex-basis: 1` property |

## Misc

### Box shadow

Add or override the `box-shadow` property.

| Class | Description |
| --- | --- |
| `bs-sm` | Add a small box-shadow (use for small elements) |
| `bs-md` | Add a default box-shadow |
| `bs-lg` | Add a large box-shadow (use for large blocks) |

### Border

Override the `border-width` property.

| Class | Value | Description |
| --- | --- | --- |
| `b-sm` | 1px | Use a small border width |
| `b-md` | 2px | Use a default border width |
| `b-lg` | 4px | Use a large border width |

### Border radius

Add a custom `border-radius`.

| Class | Value | Description |
| --- | --- | --- |
| `br-0` | 0 | Remove the border radius |
| `br-sm` | 4px | Add a small border radius |
| `br-md` | 8px | Add a default border radius |
| `br-lg` | 16px | Add a large border radius |
| `br-50` | 50% | Add a 50% border radius (use for rounded shapes, need to have the same height and width ) |
