# ALX CSS Basic Project

This directory introduces basic CSS styling to existing HTML files.

## Task 0: Some early styling

- Created a new directory: `css_basic`.
- Copied preexisting `index.html` and `tweets.html`
- Created `base.css` with starter CSS rules.
- Created an empty `styles.css`.
- Added the following lines inside the `<head>` tag of each HTML file:

```html
<link href="base.css" rel="stylesheet" />
<link href="styles.css" rel="stylesheet" />
```

---

## Task 1: Positioning

- Applied `display: flex` to `<body>` and `<main>`.
- Set `flex-direction: column` for `<body>`, and `row` for `<main>`.
- Applied `flex: auto` to `<main>` for automatic sizing.
- Set `flex: 2` on `<article>` and `flex: 1` on `<aside>` to achieve the ⅔ : ⅓ width distribution.
- Enabled vertical scroll in both content areas with `overflow-y: auto`.

---

## Task 2: Responsive Web Design

- Added `class="works_on_smartphone"` to the `<body>` tag in `index.html`.
  - This activates mobile-friendly styles defined in `base.css` when the screen width is below 800px.
- Ensured a viewport meta tag is present in the `<head>` of `index.html` to ensure proper scaling and zoom behavior:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
