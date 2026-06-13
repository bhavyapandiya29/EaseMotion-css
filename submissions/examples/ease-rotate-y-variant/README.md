# ease-rotate-y-variant

Utility class for a smooth Y‑axis rotation with a customizable duration via the `--ease-rotate-y-duration` CSS custom property.

## Usage
```html
<link rel="stylesheet" href="path/to/style.css" />
<div class="ease-rotate-y-variant" style="--ease-rotate-y-duration: 1.5s;">Hover me</div>
```

- Hover/focus rotates the element 180°.
- The duration defaults to `0.8s` but can be overridden.
- Respects `prefers-reduced-motion`.

## Demo
Open `demo.html` in this folder.

## Implementation Details
- `perspective: 1000px` for 3D effect.
- Transition uses the library’s cubic‑bezier curve.
- `will-change: transform` for performance.

## Compatibility
All modern browsers supporting CSS transforms, transitions, and custom properties.

---
*Resolves [Issue #7064](https://github.com/SAPTARSHI-coder/EaseMotion-css/issues/7064).*
