# 168 Park Selayang Residences Website

A static marketing website built to showcase the 168 Park Selayang residential development. The project uses modern HTML, CSS, and JavaScript with Bootstrap, AOS, GSAP, Owl Carousel, and EmailJS integration.

## Overview

This project is a multi-page brochure site for a residential development. It includes home, concept, gallery, floor plan, residence detail, mortgage calculator, and contact pages. The website is designed for easy local preview and simple deployment as a static site.

This website was created to take an older site and transform its UI/UX and frontend into a fresh, modern upgrade.

## Features

- Responsive multi-page layout with Bootstrap 5
- Hero section, amenities carousel, and feature cards
- Floor plan gallery with modal preview and filtering
- Mortgage calculator with monthly payment breakdown
- Contact form using EmailJS placeholders
- Animated entrance effects using GSAP and AOS
- Image carousel powered by Owl Carousel
- Sticky navbar and responsive mobile menu
- Static content with no backend required

## Tech stack

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- GSAP + ScrollTrigger
- AOS (Animate On Scroll)
- Owl Carousel 2
- EmailJS (frontend contact form)
- Local assets for images and layout media

## Project structure

```text
residential project website/
├── assets/                 # Images and media assets
├── css/
│   └── styles.css          # Custom styling
├── js/
│   └── script.js           # Page behavior and interactions
├── bole.html               # Bole residence page
├── concept.html            # Concept and design page
├── contact.html            # Contact page
├── floor-plan.html         # Floor plans page
├── gallery.html            # Gallery page
├── index.html              # Home page
├── lush.html               # Lush residence page
├── mortgage.html           # Mortgage calculator page
└── README.md               # Project documentation
```

## Page overview

- `index.html` — Landing/home page with project introduction and amenities
- `concept.html` — Conceptual design and vision for the development
- `gallery.html` — Visual gallery showcasing property images
- `floor-plan.html` — Floor plan displays, modal preview, and filters
- `bole.html` — Details for Bole residence type
- `lush.html` — Details for Lush residence type
- `mortgage.html` — Mortgage calculator and financial estimate page
- `contact.html` — Contact/inquiry form with submission handling

## Running the project

This is a static website, so no build tools or server backend are required.

### Option 1: Open directly in your browser

1. Open `index.html` or any page file in a modern browser.
2. Verify the page loads styles from `css/styles.css` and scripts from `js/script.js`.

### Option 2: Use VS Code Live Server

1. Install the **Live Server** extension for VS Code.
2. Open this project folder in VS Code.
3. Click `Go Live` in the status bar.
4. Open the local address it displays (for example `http://127.0.0.1:5500/`).

### Option 3: Use a local HTTP server

From the project root folder, run one of these commands:

- Python 3:
  ```sh
  python -m http.server 8000
  ```
- Node.js:
  ```sh
  npx http-server -p 8000
  ```

Then open `http://localhost:8000/` in your browser.

## Customization

- Update images in `assets/` to replace placeholders and property visuals.
- Edit `css/styles.css` to adjust colors, typography, spacing, and responsive layout.
- Update `js/script.js` for carousel settings, form handling, mortgage logic, and modal behavior.
- Replace EmailJS service and template IDs in `js/script.js` to enable contact form submissions.

## Notes

- The contact form currently uses placeholder `YOUR_SERVICE_ID` and `YOUR_TEMPLATE_ID` values. Replace these with real EmailJS credentials to enable email delivery.
- The mortgage calculator is an estimate tool and does not replace financial advice.
- The site is best served from a local web server for correct asset loading and script behavior.

## Author

Developed by **Dexufy** and **tristantze**.

GitHub: [@Dexufy](https://github.com/Dexufy) / [@tristantze](https://github.com/tristantze)

## License

This project is provided as a static demo site for educational and presentation purposes.
