# TeenCraiova

A platform made for teens to access in order to achieve their goals or gather information about any type of social gathering/activity.

## Table of Contents
- About
- Features
- Tech stack
- Getting started (Development)
- Deployment / Hosting
- Project structure
- How to contribute
- Roadmap
- License & Contact

## About
TeenCraiova is a static front-end platform (HTML/CSS, with a small amount of JavaScript) that helps teenagers find and organize social activities, discover local events, set personal goals, and access resources. The repo holds the client-side code and assets.

## Features
- Event listings (static examples / templates)
- Personal goals / planner UI
- Resource pages (articles, tips)
- Responsive layout for mobile and desktop
- Reusable UI components (cards, modals, navigation)

## Tech stack
- HTML (primary)
- CSS (responsive layout, custom styling)
- JavaScript (small interactive components)

No backend is included in this repository — it's meant to be a front-end prototype or static site.

## Getting started (Development)
Prerequisites:
- Modern browser (Chrome, Firefox, Edge)
- Optional: Node.js + Live Server / http-server for local dev

Local preview:
1. Clone the repo:
   git clone https://github.com/stectorius/teencraiova.git
2. Open `index.html` in your browser, or serve the folder:
   - With VS Code Live Server: right-click `index.html` → "Open with Live Server"
   - With http-server: npm i -g http-server && http-server ./ -c-1

Working on styles or markup:
- Edit the `.html` files in the root or `pages/` folder (if present).
- Edit the `.css` files in `css/` (or wherever styles are kept).
- JavaScript components (if any) are under `js/`.

## Deployment / Hosting
This project can be hosted as a static site. Good options:
- GitHub Pages (branch `main` → GitHub Pages)
- Netlify / Vercel (drag & drop or connect repo)
- Any static file host (S3 + CloudFront, Firebase Hosting, etc.)

## Project structure (example)
- index.html — home page
- /assets — images, icons, fonts
- /css — stylesheets
- /js — small interactive scripts
- /pages — subpages (events, resources, about)
Adjust paths if the actual repo structure differs.

## How to contribute
- Fork the repo
- Create a feature branch: `git checkout -b feature/your-feature`
- Make changes, keep commits focused and descriptive
- Open a pull request describing the change and screenshots if applicable

Guidelines:
- Keep HTML semantic and accessible
- Follow existing CSS naming patterns
- Keep JavaScript minimal and unobtrusive

## Roadmap (suggestions)
- Add CMS or backend to store events and user goals
- Improve accessibility (ARIA, keyboard navigation)
- Add search and filters for events
- Add localization support

## License & Contact
Specify a license file (e.g., MIT) in the repo root if you want to permit reuse.

Questions? Contact: https://github.com/stectorius
