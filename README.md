# Judah Odoom — Portfolio (Assignment-Ready Starter)

This site is built to satisfy the rubric: **fluid responsive design**, **separate CSS files for each viewport**, **no Flexbox**, **HTML5 video**, and basic **CSS transforms** for interactivity.

## Viewports (and why)
- **Mobile:** `<= 480px` — common small phones; reduces layout to a single column for readability.
- **Tablet:** `481px–1024px` — covers most tablets in portrait/landscape; uses two-column floats.
- **Laptop/Desktop:** `>= 1025px` — spacious layout with float-based grid cards, max width 1100px for comfortable line length.

These breakpoints are declared using `<link>` tags with `media` attributes for **three separate CSS files** per the course requirement.

## Color Scheme
- Gradient background: `#05176B -> #000000`
- Base colors: `#05176B`, `#000000`, `#292929`
- Text: `#FFFFFF`
- Font: Arial

## Where Gradients Are Used
- Applied to the **page background** via `linear-gradient(180deg, #05176B, #000000)` in all stylesheets.

## HTML5 Video
- `video.html` contains a native `<video>` player with `controls` and `poster`.  
- Add files to `/assets/intro.mp4` and `/assets/intro.ogv` (optional Ogg). Replace `/assets/video-poster.jpg` if you want a custom poster.

## Notes
- Layout uses **floats and percentage widths** (no Flexbox) to stay within the course constraints.
- Simple hover effects with `transform` (scale/translate) to showcase CSS transforms without JavaScript.
- Contact form uses HTML5 validation and a phone pattern that accepts `(647) 890 3643` or `647-890-3643`.

## How to Run
Open `index.html` in a browser. For GitHub Pages:
1. Create a repo (e.g., `judah-portfolio`), push files.
2. Enable Pages: **Settings → Pages → Deploy from branch → `main` / `/root`**.
3. Your site will be live at the URL shown in Pages settings.

