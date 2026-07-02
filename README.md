# travellingwebsite
# Almanac — Private Journeys, Unhurried

A 5-page responsive travel website for a boutique trip-planning studio. Built with pure HTML and internal CSS — no JavaScript, no build tools, no dependencies beyond Google Fonts.

**Live site:** yourtravellingwebsiteyp.netlify.app

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero, studio intro, featured journeys, stats, testimonial |
| Destinations | `destinations.html` | Eleven regions, filterable by type, ledger-style listing |
| Packages | `packages.html` | Three pricing tiers + FAQ |
| About Us | `about.html` | Studio story, timeline, values, planner profiles |
| Contact Us | `contact.html` | Contact form, studio info, inline SVG map |

## Features

- Fully responsive layout (desktop, tablet, mobile) with a CSS-only hamburger menu (checkbox hack, no JS)
- Page-load and scroll-friendly CSS animations: hero reveal sequence, hand-drawn ink underline, staggered fade-ups, hover micro-interactions
- Consistent header/footer across all pages
- Custom typography pairing: **Cormorant** (display), **Jost** (body), **IBM Plex Mono** (labels/dates)
- `prefers-reduced-motion` respected; visible keyboard focus states

## Tech

- HTML5
- CSS3 (custom properties, Grid, Flexbox, keyframe animations)
- Google Fonts (loaded via `@import`)
- Unsplash images (hotlinked via URL)
- No JavaScript, no frameworks, no build step

## Project Structure

```
├── index.html
├── destinations.html
├── packages.html
├── about.html
├── contact.html
└── README.md
```

## Running Locally

No build step required. Clone the repo and open `index.html` in a browser, or serve it with any static server:

```bash
git clone <your-repo-url>
cd <repo-folder>
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment (Netlify)

1. Push this repo to GitHub.
2. In Netlify: **Add new site → Import an existing project → connect your GitHub repo**.
3. Build command: leave blank. Publish directory: `/` (project root).
4. Deploy. Netlify will serve `index.html` as the homepage automatically.

Alternatively, drag and drop the project folder directly onto [app.netlify.com/drop](https://app.netlify.com/drop).

## Credits

Images sourced from [Unsplash](https://unsplash.com). Fonts from [Google Fonts](https://fonts.google.com).

