---
layout: "default"

title: "Conventions"
subtitle: "Here are all the naming rules for css classes and scss files, and the syntactic conventions of css properties."
---

## Classes naming

### BEM Markdown

The CSS styles are based on an adapted version of BEM terminology (for Block Element Modifier).

- **Blocks** are the main element of the component, in most cases the parent container.
- **Elements** are the children of the component, the "elements" within.
  - The element name is separated from the block name with a double underscore `__`.
  - An element is always part of a block, and **should never be used separately** from the block.
  - In rare cases, parents can be elements (for instance `accordion__wrapper` which wraps all the `accordion` elements).
- **Modifiers** are classes we add to change the appearance of a block (e.g. `button--error`, `alert--success`).
  - The modifier name is separated from the class name with a double hyphen `--`.
  - In rare cases, elements can have modifiers (eg. `grid__item--6`).

#### Example

```html
<!-- block with modifier -->
<div class="alert alert--success"> 
  <!-- elements -->
  <p class="alert__title"></p> 
  <p class="alert__subtitle"></p> 
  <button type="button" class="alert__close"></button> 
</div>
```

#### Useful links

- [bem.info](https://en.bem.info/methodology/quick-start/)<br>
- [getbem.com](http://getbem.com/introduction/)


### Other conventions

Try as much as possible to express modifiers with one word. If you need more than one word, use lower camel case (eg. `button--fullWidth`). Never use a single dash `-` to separate words if a modifier has multiple words.

In some cases, multiple instances of the same block are contained in a parent container. In such cases, the parent container class is given the same class as the component block on the plural form (eg. `tabs` is the container of multiple `tab`).

Never use abbreviations (ie. never write `img` for image, or `btn` for button), except for sizes (`sm`, `md`, `lg`, etc.) and for some [global]({% link _utils/global.md %}) classes.

## File naming

All scss files start with an underscore `_`.

For files in the pages folder, always use the same name for the SCSS file as the blade file.

If you need to have multiple words in your file, separate them with a dash `-`.

## Syntax rules

Always express sizes by multiplying the [`$spacing`]({% link _utils/variables.md %}#spacing) variable. 

For fonts, use `rem` units.
