# Day 08 – 2026-02-23

## 📌 Focus of the Day

Mastering External CSS, Typography (Web Fonts & Icons), and Advanced Background Properties.

## 📚 What I Learned

- **CSS Implementation Methods**
  - Difference between **Inline**, **Internal**, and **External** CSS.
  - Using `<link rel="stylesheet" href="path/to/style.css">` for better project structure.
- **Typography & Icons**
  - Using `@font-face` to implement custom local fonts (IranSans).
  - Integrating **FontAwesome** for scalable vector icons.
- **Advanced Backgrounds**
  - `background-image` & `background-repeat` (repeat, no-repeat, repeat-x/y).
  - `background-size`: Deep dive into `cover`, `contain`, and manual units (px/%).
  - `background-position`: Using coordinates for **CSS Sprites** (slices.png).
  - `background-attachment`: Creating parallax-like effects with `fixed` vs `scroll`.
- **Box Visuals & Clipping**
  - **Simple Borders**: Shorthand property (`border: 1px solid black`).
  - **background-clip**: Controlling where the background is painted (`border-box`, `padding-box`, `content-box`).
  - **background-origin**: Controlling the background starting point relative to the box model.

## 🛠️ Practice

- Created `Example6.html` as the main practice file.
- Separated logic by linking an external `style.css`.
- Experimented with background positioning using a sprite image (`slices.png`).
- Applied different clipping and origin behaviors on containers with padding and borders.

## 🧠 Key Takeaways

- **External CSS** is the professional way to keep HTML clean and styles reusable.
- `background-clip` masks the background, while `background-origin` determines its placement.
- `background-size: cover` is essential for responsive full-width sections.
- Using `fixed` attachment is a simple way to add depth to a webpage.

## ✅ Tomorrow’s Plan

- **Gradients**: Explore **Linear Gradient** backgrounds and **Faded** effects.
- **Tools**: Master **cssgradient.io** for generating complex gradients.
- **Shorthand**: Learn the **All-in-one background property** (combining color, image, position, size, repeat, origin, clip, and attachment).
- **Compatibility**: Use **caniuse.com** to check browser support for CSS features.
- **Animations**: Explore **cubic-bezier.com** for custom transition-timing functions.
- **HTML Lists**: Practice **Ordered (ol)** and **Unordered (ul)** lists.
- **Borders**: Deep dive into the `border` shorthand (width, style, color).
