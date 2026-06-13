# ease-rotate-y-2

Utility class for a smooth Y‑axis rotation (3D flip) effect – a variant of `ease-rotate-y`.

## Usage
```html
<link rel="stylesheet" href="path/to/style.css" />
<div class="ease-rotate-y-2">Hover me</div>
```

- The element rotates 180° on hover/focus.
- Respects `prefers-reduced-motion` – animation is disabled for users who request reduced motion.

## Demo
Open `demo.html` in this folder to see the effect.

## Implementation Details
- `perspective: 1000px` for a realistic 3D feel.
- Transition uses `cubic‑bezier(0.4, 0, 0.2, 1)` to match the library’s easing curve.
- `will-change: transform` hints the browser for smoother rendering.

## Compatibility
Works in all modern browsers that support CSS transforms and transitions.

---
*Resolves [Issue #7063](https://github.com/SAPTARSHI-coder/EaseMotion-css/issues/7063).*
