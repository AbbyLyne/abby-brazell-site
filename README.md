# Abby Brazell — personal site

** WIP - Live at [abbybrazell.com](https://abbybrazell.com)**

The source for my personal website: a short introduction, my experience, my CV and where to find me. I'm a data analyst based in the Bay of Plenty, New Zealand, and this site is also where I'll share the projects I'm building.

## How it's built

- **Hand-written HTML and CSS.** No framework, no build step and no JavaScript beyond a one-line footer year, so the site loads fast and is easy to maintain.
- **Responsive with automatic dark mode,** using CSS custom properties for the whole colour theme.
- **Hosted on Cloudflare** (Workers static assets), deployed from this repo through Cloudflare's GitHub integration. Every push to `main` goes live automatically.
- **Custom domain and SSL** managed through Cloudflare DNS.

## Repository layout

```
public/
  index.html    the page
  styles.css    theme, layout and responsive rules
  404.html      not-found page
  cv.pdf        downloadable CV
wrangler.jsonc  Cloudflare deployment config
```

## Roadmap

- [x] About, experience, CV and links
- [ ] First project write-up
- [ ] Project pages as new work is published

## Running locally

Open `public/index.html` in a browser. Nothing to install.

To change the colour scheme, edit `--accent` at the top of `public/styles.css`; all the other colours are defined there too.
