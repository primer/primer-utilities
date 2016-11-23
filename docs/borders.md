---
title: Borders
status: New release
status_issue: https://github.com/github/design-systems/issues/72
---

Utilities for borders, border radius, and box shadows.

- [Border width, style, and color utilities](#border-width-style-and-color-utilities)
- [Rounded corners](#rounded-corners)
- [Box shadows](#box-shadows)

## Border width, style, and color utilities

The base border utility applies a solid, 1px border, with a default gray color.

```html
<div class="border">
  .border
</div>
```

Borders can be applied to a specific edge or to the Y axis.

```html
<div class="d-flex mb-3">
  <div class="border-left col-3">
    .border-left
  </div>
  <div class="border-top col-3">
    .border-top
  </div>
  <div class="border-bottom col-3">
    .border-bottom
  </div>
  <div class="border-right col-3">
    .border-right
  </div>
</div>
<div class="border-y">
  .border-y
</div>
```

Override default border colors with blue, red, and gray border color utilities.

```html
<div class="border border-blue mb-2">
  .border-blue
</div>
<div class="border border-blue-dark mb-2">
  .border-blue-dark
</div>
<div class="border border-red mb-2">
  .border-red
</div>
<div class="border border-red-dark mb-2">
  .border-red-dark
</div>
<div class="border border-gray-light mb-2">
  .border-gray-light
</div>
<div class="border border-gray-dark mb-2">
  .border-gray-dark
</div>
```

Remove borders from all sides or a single side with `.border-0`, `.border-top-0`, `.border-right-0`, `.border-bottom-0`, `.border-left-0`.

```html
<div class="Box border-top-0">
  .border-top-0
</div>
```

## Rounded corners

Add or remove rounded corners: `rounded-0` removes rounded corners, `rounded-1` applies a border radius of 3px, `rounded-2` applies a border radius of 6px.

```html
<div class="Box rounded-0 mb-2">
  .rounded-0
</div>
<div class="border rounded-1 mb-2">
  .rounded-1
</div>
<div class="border rounded-2">
  .rounded-2
</div>
```

## Box shadows

Apply a box-shadow with `box-shadow` or a larger box-shadow `box-shadow-large`.

```html
<div class="Box box-shadow mb-4">
  .box-shadow
</div>
<div class="box-shadow-large">
  .box-shadow-large
</div>
```
