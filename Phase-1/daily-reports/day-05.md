# Day 05 – 2026‑02‑13

## 📌 Focus of the Day

- Transition from inline CSS to internal CSS
- Understand and practice CSS classes and IDs
- Learn different display types (block, inline, inline‑block)
- Get introduced to Flexbox basics
- Practice advanced CSS selectors (descendant & child selectors)
- Continue Phase 1: Learning Basic HTML & CSS

## 📚 What I Learned

### Internal CSS

Using the `<style>` tag inside the `<head>` or `<body>` to separate structure from styling.
This approach improves readability, reusability, and maintainability compared to inline CSS.

###  CSS Classes & IDs

- `Class` (.) → reusable styling for multiple elements
- `ID` (#) → unique styling for a single element

Learned when to use each and why IDs should not be repeated.

### Display Property

- block → takes full width (e.g. `div`, `p`)
- inline → takes only content width (e.g. `span`, `a`)
- inline-block → inline behavior with block sizing (`width` & `height`)

### Flexbox Basics

- `display: flex`
- `justify-content` → horizontal alignment
- `align-items` → vertical alignment

Learned how Flexbox simplifies layout alignment compared to margins and floats.

### CSS Selectors

- Descendant selector (.parent .child)
- Child selector (.parent > .child)
- Understanding how nesting affects style inheritance and specificity

## 🛠️ Practice

- Created train1.html to:

* Combine inline CSS with internal CSS
* Apply classes to multiple `<a>` elements
* Use IDs for styling colored boxes

- Created Example3.html for deeper CSS concepts:

* Tested display: block, inline, and inline-block
* Practiced Flexbox alignment scenarios
* Experimented with nested elements and selector behavior

- Used comments to isolate and test each concept independently

## 🧠 Key Takeaways

- Internal CSS is much cleaner and more scalable than inline CSS.
- Classes are ideal for reusable styles; IDs should be unique and specific.
- display fundamentally changes how elements behave in layout.
- Flexbox makes alignment intuitive and reduces layout complexity.
- Understanding selectors is critical for controlling complex layouts.

“Clean structure + clear CSS logic = maintainable code.”

## ⚠️ Challenges

- Visualizing Flexbox alignment without over-testing properties

## ❓ Questions / Confusions

- How deep should nesting go before CSS becomes hard to maintain?

## ✅ Tomorrow’s Plan

- Universal selector (`*`)
- OR selector (`,`)
- AND selector (combined selectors)
- Adjacent sibling selector (`+`)
- General sibling selector (‍‍`~`)
- Attribute present selector (`[attr]`)
- Use internal CSS
- Write short, clear examples
- Comment each selector in one line
- Understand when and why to use each selector
- Be comfortable reading and writing them
