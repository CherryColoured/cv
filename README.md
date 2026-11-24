# Diego Jacobs — Professional Portfolio

Bilingual professional portfolio (Spanish / English), designed for recruiter review. The site is static and self-contained: no frameworks, external JavaScript libraries, backend or third-party requests are required.

## Package contents

- `index.html` — portfolio website.
- `assets/diego-jacobs.jpg` — profile photograph supplied for this portfolio.
- `downloads/Diego_Jacobs_CV_Ejecutivo_ES.pdf` — Spanish executive CV (2 pages).
- `downloads/Diego_Jacobs_Executive_CV_EN.pdf` — English executive CV (2 pages).

## Open locally

1. Extract the ZIP file.
2. Keep the `assets` and `downloads` folders beside `index.html`.
3. Open `index.html` in Chrome, Firefox, Safari or Edge.
4. Use the ES / EN selector. The CV download button follows the selected language.

## Personalization

- Replace `assets/diego-jacobs.jpg` to change the photograph, keeping the same filename or updating the image path in `index.html`.
- Replace either PDF inside `downloads/` to update the downloadable CV. Keep the filenames unchanged so the site buttons continue to work.
- Edit the bilingual text directly in `index.html`. Content is paired through `.lang-es` and `.lang-en` spans.

## Technical notes

- Static HTML, CSS and vanilla JavaScript.
- Relative asset links; works from a local folder and under a GitHub Pages project URL.
- Responsive layout, keyboard-accessible lab-layer controls and reduced-motion support.
- No external fonts, analytics, trackers or CDN dependencies.
