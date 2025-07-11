# 🌌 Spica CSS Framework

**Spica** is a responsive-first CSS utility framework built with Sass. It provides modular, breakpoint-aware utilities for color, spacing, and layout control—crafted to be scalable, predictable, and developer-friendly.

---

## ✨ Features

- **Responsive Color Utilities**  
  Easily switch background and text colors across breakpoints using intuitive class names.

- **Spacing System**  
  Utility classes for margin and padding with directional control (`mt-*`, `px-*`, etc.) and fractional values.

- **Breakpoint Engine**  
  Customize breakpoint keys and generate variants like `sm:bg-*`, `md:mt-*`, etc.

- **String-Safe Interpolation**  
  Fractional spacing values like `0.5` are sanitized into safe class names (`mt-0_5`).

- **Debug Grid**  
  Included HTML layout for previewing utilities across screen sizes.

- **Viewport Meta Compatibility**  
  Ensures responsive behavior works correctly across all devices.

---

## 🧪 Example

```html
<div class="bg-black md:bg-blue-400 lg:bg-red-400 text-white p-4">
  Responsive color block
</div>

<div class="mt-1 md:mt-4 lg:mt-8">
  Responsive margin example
</div>
