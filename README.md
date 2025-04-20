# Netflix Clone Static

A visually rich Netflix landing page clone built using plain HTML, CSS, and Vanilla JavaScript.

## Features
- Fully responsive Netflix-style landing page
- Accordion FAQ section (animated, one open at a time)
- Animated wave heading on hero section
- Custom animated cursor using GSAP
- Trending carousel with scroll buttons
- Clean, modern UI with CSS effects

## Demo
Open `index.html` in your browser to view the landing page.

## Getting Started
1. **Clone this repository**
   ```bash
   git clone <repo-url>
   cd netflix-clone-static
   ```
2. **Open the project**
   - Open `index.html` directly in your browser (no build step required).

## Project Structure
- `index.html` — Main HTML file for the landing page
- `index.css` — All styles for layout, animations, and responsiveness
- `assets/` — Images and icons for the page

## Notable Implementations
- **FAQ Accordion**: Click a question to expand/collapse the answer. Only one answer can be open at a time. Smooth animation using CSS transitions.
- **Animated Heading**: Hero section heading animates each word in a wave pattern.
- **Custom Cursor**: Red circular cursor follows mouse movement using GSAP animation library.
- **Trending Carousel**: Scrollable trending section with left/right navigation buttons.

## Dependencies
- [GSAP](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js) (for cursor animation, loaded via CDN)

## Customization
- You can easily update images in the `assets/` folder or change the FAQ content in `index.html`.
- Modify styles in `index.css` for further visual changes.

## Credits
- Inspired by Netflix's official landing page design.
- Built for Hackathon purposes.

---

Feel free to fork and customize!
