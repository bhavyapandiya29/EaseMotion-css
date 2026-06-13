# ease-fade-in-out

Utility class for a smooth opacity fade‑in/fade‑out animation using keyframes.

## Usage
```html
<link rel="stylesheet" href="path/to/style.css" />
<div class="ease-fade-in-out">Fade me</div>
```

- The element fades in and out continuously.
- Duration can be customized via `--ease-fade-duration` custom property.
- Respects `prefers-reduced-motion` – disables animation for users who request reduced motion.

## Demo
Open `demo.html` in this folder.

## Implementation Details
- Keyframes `ease-fade-in-out` handle the opacity cycle.
- `animation` uses the library’s default cubic‑bezier curve and loops infinitely.
- `will-change: opacity` hints the browser for smoother rendering.

## Compatibility
All modern browsers supporting CSS animations and custom properties.

---
*Resolves [Issue #7068](https://github.com/SAPTARSHI-coder/EaseMotion-css/issues/7068).*
