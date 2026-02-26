# Day 10 – 2026-02-25

## 📌 Focus of the Day

- Working with Lists, Borders, Text Overflow, and Visual Effects in CSS.

## 📚 What I Learned

### Lists (Ordered & Unordered)

- Customized ordered lists (`<ol>`) by removing default numbering using `list-style: none;`.
- Styled unordered lists (`<ul>`) with custom bullets such as `square`.

### Borders

- Used border shorthand syntax:  
  `border: width style color;`
- Styled each side individually (`border-top`, `border-right`, etc.) with different styles and colors.

### Text Overflow

- Learned how to control overflowing text using:
  - `text-overflow: clip` (default)
  - `text-overflow: ellipsis`
- Understood required properties:
  - `overflow: hidden;`
  - `white-space: nowrap;`
- Noted that custom string overflow works only in Firefox.

### `<p>` vs `<pre>`

- `<p>` collapses whitespace and ignores line breaks.
- `<pre>` preserves spaces, tabs, and line breaks exactly as written.

### Image Filters

- Practiced image effects using `filter`:
  - `blur()`
  - `brightness()`
  - `contrast()`
  - `grayscale()`
  - `opacity()`

### Filter vs Backdrop-Filter

- `filter`: affects the element itself.
- `backdrop-filter`: affects the background behind the element (useful for glassmorphism effects).

### Text & Box Styling

- Removed link underlines using `text-decoration: none;`
- Improved paragraph readability with:
  - `line-height`
  - `text-align: justify`
- Applied:
  - `text-shadow` for text depth
  - `box-shadow` (including `inset`) for element elevation

## 🧠 Key Takeaways

- Lists and borders are highly customizable with simple CSS properties.
- Text overflow control is essential for clean UI layouts.
- `<pre>` is ideal for code or formatted text.
- Filters add powerful visual effects with minimal code.
- `backdrop-filter` creates modern UI blur effects when supported.

## ✅ Tomorrow’s Plan

- Pseudo-elements: `::before` & `::after` (using `content: ""`)
- Radial Gradients (default `ellipse`)
- CSS Transforms:
  - `translate(Xpx, Ypx)`
  - `rotate(deg)`
  - `scale(X%, Y%)`
  - `skew(Xdeg, Ydeg)`
