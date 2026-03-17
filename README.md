# muku.css (v0.0.7)
> A humble, zero-specificity CSS reset for the modern web.

Designed by **Shigeru Iwasaki**, **muku.css** is a "MUKU" (purity) state for your web documents. It removes the "noise" of browser defaults without imposing its own will.

## The Philosophy of "MUKU" (無垢)
In Japanese culture, **muku** represents a state of being pure, untainted, and free from worldly desires (Bonno). 

- **Purity:** Free from browser-specific "opinions."
- **Innocence:** A blank canvas for your creativity.
- **Solidity:** A reliable, consistent foundation.

## Key Features
- **Zero Specificity:** All rules are wrapped in `:where()`, keeping specificity at 0.
- **2026 Ready:** Native support for `100dvh` and `field-sizing: content`.
- **Accessibility First:** Protected `:focus-visible` styles to ensure usability for everyone.
- **Cascade Layered:** Built within `@layer reset` to prevent conflicts with your styles.

## Quick Start
Link to `css/muku.css` in your HTML:

```html
<link rel="stylesheet" href="css/muku.css">
