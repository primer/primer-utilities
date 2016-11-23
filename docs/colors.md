---
title: Colors
status: New release
status_issue: https://github.com/github/design-systems/issues/97
---

**Needs further documentation for text and background colors.**

## Link utilities
Base link styles turn links blue and apply an underline on hover. You can override the base link styles with text color utilities and the following link utilities. **Bear in mind that link styles are easier for more people to see and interact with when the changes in styles do not rely on color alone.**

Use `link-gray` to turn the link color to `$text-gray` and remain hover on blue.

```html
<a class="link-gray" href="#">link-gray</a>
```

Use `link-gray-dark` to turn the link color to `$text-gray-dark` and remain hover on blue.

```html
<a class="link-gray-dark"  href="#">link-gray-dark</a>
```

Use `.muted-link` to turn the link light gray in color, and blue on hover or focus with no underline.

```html
<a class="muted-link" href="#">muted-link</a>
```

Use `link-hover-blue` to make any text color used with links to turn blue on hover. This is useful when you want only part of a link to turn blue on hover.

```html
<a class="text-gray-dark no-underline" href="#">
  A link with only part of it is <span class="link-hover-blue">blue on hover</span>.
</a>
```
