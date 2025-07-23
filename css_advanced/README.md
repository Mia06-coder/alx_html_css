# Advanced CSS Project – Figma to HTML & CSS

Welcome to the **Advanced CSS Styling** project!

In this project, I’m replicating a web page layout from a Figma design using pure HTML and CSS. This exercise helps me deepen my understanding of layout techniques, visual alignment, spacing, and responsive styling using modern CSS.

---

## 🎯 Objectives

- Replicate a high-fidelity design from Figma using pure CSS.
- Practice advanced styling techniques including:
  - Positioning
  - Flexbox/Grid layouts
  - Typography and spacing
  - Shadows and visual hierarchy
  - Responsive behavior (mobile-first approach)
- Use and optimize assets (images, fonts) provided in the design.

---

## 📁 Project Structure

```plaintext
css_advanced/
│
├── index.html
├── styles.css
├── images/
│ └── (assets from Figma design)
└── README.md
```

---

## 💡 Notes

- Rounded float values from Figma to the nearest whole numbers where needed.
- Use semantic HTML tags for better structure and accessibility.
- Organize styles using a **mobile-first** approach.
- Follow accessible and scalable naming conventions (BEM-like or semantic).

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mia06-coder/alx_html_css.git
   cd css_advanced
   ```
2. Open index.html in your browser.
3. Edit files with any code editor of your choice (e.g., VS Code).

## 🎨 Original Figma Design

Here is the design I’m working on replicating:

![Figma Design Screenshot](./images/figma-design.png)

📌 Make sure to duplicate the [design](https://www.figma.com/design/lf3pF5UxyelYnpSPKQeoc0/Homepage--Copy-?node-id=0-1&t=oy5udNjvklosO7Yl-1) into your own Figma drafts to inspect properties and download assets.

## 🛠️ Styling Progress

This section will be updated with specific styling tasks and progress as I complete each one.

- Base styles (fonts, colors, resets)
- Header layout and positioning
- Hero section with background and buttons
- Content sections
- Footer
- Responsive tweaks

## ✅ Tasks Completed

### Task 1: Import the Style

- Created an empty `styles.css` file.
- Linked it to `index.html` using a `<link>` tag inside the `<head>`.
- This setup allows styling through an external CSS file.

### Task2 : Header & Hero Styling

This update includes the following changes based on the provided Figma file:

- Mobile-first layout for header and hero (banner).
- Accurate implementation of dimensions, padding, spacing, and typography.
- Shared background image applied across both sections using a wrapper div.
- Fonts imported via @font-face (declared only once for each variation).
- Clean, semantic HTML with simple CSS selectors for clarity and maintainability.

### Task 3 : Testimonial Styling

- Styled the testimonial (quote) section based on the Figma specs.
- Used mobile-first approach for responsiveness.
- Avatar stacks above text on mobile and aligns horizontally on larger screens.
- Typography and spacing match the design system.

### Task 4 : Tutorials Styling

- Added responsive grid layout for tutorial cards.
- Cards are fixed at 255px width, center-aligned.
- Used mobile-first grid layout with breakpoints for tablet (2 columns) and desktop (4 columns).
- Followed BEM naming convention and organized structure with consistent spacing and padding.

### Task 5: Membership Styling

- Responsive Membership section layout
  - Mobile: 1 column
  - Tablet: 2 columns
  - Desktop: 4 columns
- Clean, semantic CSS using custom properties
- Styled CTA button and icon display

### Task 6: FAQ Styling

- A fully responsive FAQ section, styled based on the Figma design.

#### Code Overview - HTML Structure

```html
<section class="faq">
  <h2 class="faq__title">F.A.Q</h2>
  <div class="faq__block">
    <div class="faq__column">
      <!-- FAQ item 1 -->
      <!-- FAQ item 2 -->
    </div>
    <div class="faq__column">
      <!-- FAQ item 3 -->
      <!-- FAQ item 4 -->
    </div>
  </div>
</section>
```

## 📌 Author

**Mia** – Software Developer in training 💻
[LinkedIn](https://www.linkedin.com/in/mia-mudzingwa)
