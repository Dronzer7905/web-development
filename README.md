# Personal Portfolio Website

A responsive single-page portfolio to showcase your bio, projects, and contact links. Uses semantic HTML and modern CSS, with a mobile hamburger menu and overlapping hero images on small screens.

## Features

- Responsive layout with mobile breakpoints (1024px, 768px, 480px)
- Accessible hamburger menu for small screens
- Projects section with image previews
- Overlapping hero images on mobile (centered and layered)
- Clean asset structure for easy scaling

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (small inline script for menu toggle)

## Project Structure

```
web-development/
├─ assets/
│  ├─ css/
│  │  ├─ style.css
│  │  └─ vars.css (optional)
│  ├─ images/
│  │  ├─ firstimg.png
│  │  ├─ firstimg1.png
│  │  ├─ image2.svg
│  │  ├─ pro1.png
│  │  └─ upcoming.jpeg
│  ├─ icons/
│  │  ├─ email.svg
│  │  ├─ insta.svg
│  │  └─ link.svg
│  └─ js/
├─ index.html
└─ README.md
```

## Getting Started

- Open `index.html` in your browser, or run a local server:
  - VS Code: Install "Live Server" → right‑click `index.html` → Open with Live Server
  - Node: `npx serve` (or any static server) from the project root

## Customization

- Brand/Name: Update the brand text in `index.html`
- About: Edit headline and description in the `#about` section
- Projects: Duplicate a `.project-card` in `index.html`, replace text and image sources
- Icons/Links: Update social links in the footer and navbar

## Asset Paths

- CSS: `assets/css/style.css`
- Images: `assets/images/<file>`
- Icons: `assets/icons/<file>`
- JS (future): `assets/js/<file>`

Place new images/icons in the corresponding folders and reference them using the paths above.

## Responsiveness Notes

- Navbar collapses to a hamburger menu under 768px
- Two hero images in `.about-images` overlap and stay centered on mobile
- Typography scales at 768px and 480px for readability

## Roadmap Ideas

- Add sections for Experience and Skills
- Blog or updates page
- Contact form (EmailJS/Netlify Forms/serverless)
- Light/Dark theme via CSS variables (`vars.css`)
- Privacy‑friendly analytics (e.g., Plausible)

## License

Personal project. Choose any license you prefer or keep it private.


