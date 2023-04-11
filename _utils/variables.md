---
layout: "default"

title: "Variables"
---

## Spacing

In order to have a consistent look and feel, all sizes and dimensions will be multiples of the `$int` variable. This variable is the base unit. It is equal to 8px.

## Colors

### System

**Common**

| Name | Value | |
| --- | --- | --- |
| `$black` | `#000A1E` | <span class="colorBlock fill--black"></span> |
| `$white` | `#FFFFFF` | <span class="colorBlock fill--white"></span> |

**Greys**

| Name | Value | |
| --- | --- | --- |
| `$grey-90` | `#1D2638` | <span class="colorBlock fill--grey90"></span> |
| `$grey-80` | `#323B4D` | <span class="colorBlock fill--grey80"></span> |
| `$grey-70` | `#485061` | <span class="colorBlock fill--grey70"></span> |
| `$grey-60` | `#626A7A` | <span class="colorBlock fill--grey60"></span> |
| `$grey-50` | `#888F9E` | <span class="colorBlock fill--grey50"></span> |
| `$grey-40` | `#B4B9C2` | <span class="colorBlock fill--grey40"></span> |
| `$grey-30` | `#CBCFD6` | <span class="colorBlock fill--grey30"></span> |
| `$grey-20` | `#E2E4E9` | <span class="colorBlock fill--grey20"></span> |
| `$grey-10` | `#EEF2F4` | <span class="colorBlock fill--grey10"></span> |
| `$grey-5` | `#F6F8F9` | <span class="colorBlock fill--grey5"></span> |

**Text**

| Name | Value | |
| --- | --- | --- | --- |
| `$text` | `$black` | <span class="body text--default">This is a default text</span> |
| `$text-alt` | `$grey-60` | <span class="body text--alt">This is an alternate text</span> |
| `$text-disabled` | `rgba($text, 0.4)` | <span class="body text--disabled">This is a disabled text</span> |
| `$text-contrast` | `$white` | <span class="textBlock fill--black"><span class="body text--contrast">This is a default contrast text</span></span> |
| `$text-contrast-alt` | `$grey-40` | <span class="textBlock fill--black"><span class="body text--contrastAlt">This is an alternate contrast text</span></span> |
| `$text-contrast-disabled` | `rgba($text, 0.4)` | <span class="textBlock fill--black"><span class="body text--contrastDisabled">This is a disabled contrast text</span></span> |

### Brand

Each brand color has three variants: `main`, `light` and `dark` (the primary and secondary have another one, `lighter`, used for background colors). Their use is automated when needed (hover states for `button`, `alert` backgroud color , etc.).

We will only display the main swatches here.

| Name | Value | |
| --- | --- | --- |
| `$primary` | `#D29132` | <span class="colorBlock fill--primary"></span> |
| `$secondary` | `#0F2D55` | <span class="colorBlock fill--secondary"></span> |
| `$highlight` | `#FFDC46` | <span class="colorBlock fill--highlight"></span> |

### Feedback

These colors are used to convey feedback to the user for an action he has performed, to emphasise a piece of information, or to give information about the state of something.

Each feedback color has three variants: `main`, `light` and `dark`. Their use is automated when needed (hover states for `button`, `alert` backgroud color , etc.).

We will only display the main swatches here.

| Name | Value | |
| --- | --- | --- |
| `$success` | `#27AE60` | <span class="colorBlock fill--success"></span> |
| `$info` | `#17A0CC` | <span class="colorBlock fill--info"></span> |
| `$warning` | `#FFDC46` | <span class="colorBlock fill--warning"></span> |
| `$error` | `#EB5757` | <span class="colorBlock fill--error"></span> |

## Typography

Even if the fonts styles are set in `resources/sass/components/_text.scss`, we will present here the font style guide.

### Headlines

We have six headline styles that follow HTML's heading tags: `.h1`, `.h2`, `.h3`, `.h4`, `.h5`, `.h6`.

### Body styles

| Class | Description |
| --- | --- |
| `subtitle` | Larger body text, used for lead text and page subtitles |
| `body` | Default body text |
| `caption` | Smaller body text, used for labels or legends |
| `overline` | Smallest body text, use scarcely |

### Modifiers 

See 
[Components > Text]({% link _components/text.md %})
For a full list of text modifiers.

## Breakpoints

Breakpoints are only used for the [responsive]({% link _utils/mixins.md %}#responsive) mixins. You don't need to concern yourself with them as they are build-in the mixin already.

As a reference, their values are:

| Name | Value |
| --- | --- |
| `$desktop-lg` | `1440px` |
| `$desktop` | `1280px` |
| `$laptop` | `1024px` |
| `$tablet` | `768px` |
| `$mobile` | `568px` |
| `$mobile-sm` | `350px` |
