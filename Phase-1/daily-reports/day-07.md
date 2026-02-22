# Day 07 – 2026-02-22

## 📌 Focus of the Day

Practicing pseudo-classes, CSS naming conventions, specificity, and positioning  
Understanding real behavior of layout and interaction-based selectors

## 📚 What I Learned

- **Pseudo-classes**
  - `:hover`, `:active`
  - `:first-child`, `:last-child`
  - `:nth-child()`, `odd`, `even`
- **box-sizing: border-box**
  - Padding included inside width and height
- **CSS Specificity Hierarchy**
  - `!important > inline style > #id > .class > tag > *`
- **Naming Conventions**
  - Camel Case
  - Pascal Case
  - BEM (Block, Element, Modifier)
- **CSS Positioning**
  - `static` (default)
  - `relative`
  - `absolute`
  - `fixed`
  - `sticky`

## 🛠️ Practice

- Example5.html added in the html folder as the practice file.
- Practiced pseudo-classes on headings and list items
- Tested `box-sizing: border-box` behavior
- Applied BEM structure in a card component
- Implemented all CSS position types with clear examples
- Used internal CSS with one-line comments for clarity

## 🧠 Key Takeaways

- Pseudo-classes depend heavily on element position and user interaction
- `position: absolute` works relative to the nearest positioned parent
- `sticky` combines relative and fixed behavior
- BEM makes CSS more readable and scalable
- Understanding specificity prevents unexpected style conflicts

## ✅ Tomorrow’s Plan

- Review and compare **CSS types**:
  - Inline CSS
  - Internal CSS
  - External CSS
- Link external stylesheet using:
  - `<link rel="stylesheet" href="address">`
- Use **@font-face** to add _IranSans_ and apply it as the site’s main font
- Learn how to use **FontAwesome** for icons
- Practice **background styles**:
  - `background-color`
  - `background-image`
- Understand and test:
  - `background-position`
  - `background-clip`
  - `background-origin`
- Practice **simple borders** and border properties
