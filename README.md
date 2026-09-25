# Portfolio Version 2

## Installation

Copy these files into the root of your existing `tech-portfolio` repository:

- `index.html`
- `style.css`
- `assets/icons/icons.svg`

Also keep `Robert-Jordan-CV-Revised.pdf` in the repository root so the CV button works.

## Required edit

Open `index.html`, search for `YOUR_LINKEDIN_URL`, and replace it with your actual public LinkedIn profile URL.

## Icons

The site uses a small local SVG sprite in `assets/icons/icons.svg`. It has no JavaScript, CDN, npm dependency or tracking. Icons are referenced like this:

```html
<svg class="icon" aria-hidden="true">
  <use href="assets/icons/icons.svg#github"></use>
</svg>
```

## Oracle Cloud

The CV button currently downloads the PDF from GitHub Pages. When your Oracle Object Storage URL is ready, replace `Robert-Jordan-CV-Revised.pdf` in the hero button with the final URL.

Do not commit Oracle credentials, keys, tokens, `.env` files or private identifiers to the public repository.

## Optional real project image

Version 2 includes a CSS-built browser preview, so it works without an image. Later you can replace it with a genuine screenshot saved as:

`assets/images/portfolio-homepage.webp`

Use descriptive alt text and keep the CSS preview until the screenshot is ready.
