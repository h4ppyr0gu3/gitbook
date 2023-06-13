---
description: Hover over a parent or child in tailwind with prefix directives
---

# Target hover in tailwind

Using `prefix-hover:...` you can apply selected hover attributes to objects with class prefix

```html
<div class="group p-5 m-5 rounded border">
  <button class="group-hover:bg-sky-400 rounded-lg p-2 m-2 border">test</button>
</div>
```

This will result in the hover class being applied when you are hovering the `div` aswell as the button
