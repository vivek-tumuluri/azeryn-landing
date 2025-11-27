# Azeryn Landing Page

Single-page marketing site for Azeryn. Built with plain HTML, CSS, and vanilla JavaScript; no build step or package manager required.

## Getting Started
- Open `index.html` in any modern browser to view the page locally. No dependencies to install.
- For local tweaks, edit `index.html` and refresh the browser; all styles and scripts are inline.

## Key Features
- Hero with animated typewriter headline and CTA buttons (waitlist modal + contact link).
- Sticky navbar that shifts to a blurred glass effect on scroll.
- Scroll-triggered reveal animations for product, how-it-works steps, and feature grids.
- Embedded Tally form surfaced in a full-screen waitlist overlay (configurable `src` link).

## Customization Tips
- Update the waitlist form URL in `index.html` (`#waitlist-iframe` `src` and fallback link).
- Swap branding, copy, or accent colors by editing the CSS variables at the top of `index.html`.
- To simplify or restyle animations, adjust the IntersectionObserver options or keyframes inline.

## Deployment
- Host the static `index.html` file on any static provider (e.g., GitHub Pages, Netlify, Vercel). No additional assets are required beyond the referenced Google Fonts.
