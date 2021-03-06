---
title: Configuration
weight: 2
---

## Updating Color

```js
// tailwind.config.js
...
theme: {
  extend: {
    colors: {
      primary: {
        light: "#fefcbf", // For lighter primary color
        default: "#b7791f", // Normal primary color
        dark: "#744210", // Used for hover, active, etc.
      },
    },
  },
},
...
```

## Primary Color Palette

{{< code html >}}

<div class="space-y-2">
  <div class="space-x-2 flex">
    <div class="bg-primary-light h-10 w-10"></div>
    <div class="border border-primary-light text-primary-light">Hello</div>
  </div>
  <div class="space-x-2 flex">
    <div class="bg-primary h-10 w-10"></div>
    <div class="border border-primary text-primary">Hello</div>
  </div>
  <div class="space-x-2 flex">
    <div class="bg-primary-dark h-10 w-10"></div>
    <div class="border border-primary-dark text-primary-dark">Hello</div>
  </div>
</div>
{{< /code >}}
