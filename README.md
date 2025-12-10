# Abhishek Verma — Portfolio

**Full-Stack Developer** — React · Java · Spring Boot · Tailwind CSS

---

## Overview

This repository contains the personal portfolio/landing page for **Abhishek Verma**. It showcases featured projects, professional experience, technical skills, and contact information. The site is built with modern, responsive UI patterns using Tailwind CSS and includes a dark mode toggle and smooth animations.

## Features

* Responsive landing page (desktop + mobile)
* Dark / Light theme with preference saved in `localStorage`
* Smooth scrolling between sections
* Animated hero and content sections
* Contact form that opens the user's email client with a pre-filled message
* Project cards with live demo and GitHub links

## Tech Stack

* HTML5
* Tailwind CSS
* Vanilla JavaScript
* Font Awesome (icons)

## File Structure

```
/ (root)
├─ index.html          # Main portfolio page
├─ projectimage/       # Project images used in cards
├─ README.md           # This file
└─ assets/             # (optional) additional assets (icons, fonts, etc.)
```

## Local Development

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. Open `index.html` in your browser (no build step required).

> If you want a local server (recommended for testing relative paths):

```bash
# using Python 3
python -m http.server 3000
# then open http://localhost:3000
```

## Customization

* Update your name, title and copy in the `<head>` and hero sections of `index.html`.
* Replace images in `projectimage/` with your own projects and update paths.
* Projects, skills, and contact details are easy to edit directly in `index.html`.

## Deployment

You can deploy the static site to any static host (Netlify, Vercel, GitHub Pages):

* For GitHub Pages: push the repo and enable Pages from the repository settings (`main` branch → `/ (root)`).
* For Netlify/Vercel: connect the repo and deploy (no build step required).

## Accessibility & Performance

* Uses semantic HTML and accessible focus styles for interactive elements.
* Prefers minimal external dependencies to reduce page weight.
* Lazy-load large images where necessary and optimize assets for production.

## Troubleshooting

* If the dark theme doesn't persist: ensure your browser allows `localStorage` and there are no restrictive privacy settings.
* If icons don't show: confirm Font Awesome stylesheet link is reachable.

## Contact

* **Email:** [abhishekverma89213@gmail.com](mailto:abhishekverma89213@gmail.com)
* **GitHub:** [https://github.com/abhiverma-143](https://github.com/abhiverma-143)
* **LinkedIn:** [https://www.linkedin.com/in/abhiverma143/](https://www.linkedin.com/in/abhiverma143/)

---

> *Updated: December 2025*

---

### License

This project is available under the MIT License. See `LICENSE` for details (optional).
