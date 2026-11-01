# abbybrazell.com

My personal website: who I am, my CV, where to find me, and the projects I'm working on.

**WIP Live site:** [abbybrazell.com](https://abbybrazell.com)

I'm a Decision Support Analyst moving further into data and analytics. This site is my home base for that, and it's also a hands-on way for me to learn web development.

## How this was built

The first version of this site was generated with an AI assistant (Claude), from a brief I wrote: a simple, clean page with my CV, an about section and my links.

From there, the site is mine to own. I'm editing the content, making the design decisions, and gradually rewriting and extending the code myself so I understand every part of it. The [learning log](#learning-log) below tracks what I've changed and what I've learned along the way.

## Tech

- **HTML and CSS only.** No framework and no build step, so every file is readable and easy to change.
- **Hosting:** Cloudflare (Workers static assets), connected to this repo. Every push to `main` deploys automatically.
- **Domain:** managed through Cloudflare DNS.

## Project structure

```
public/
  index.html      the page content
  styles.css      layout, colours and fonts (theme variables at the top)
  404.html        shown for pages that don't exist
  cv.pdf          my CV
wrangler.jsonc    Cloudflare deployment settings
```

## Running it locally

No install needed. Download or clone the repo and open `public/index.html` in a browser.

## Roadmap

- [x] Starter site generated and deployed to my domain
- [ ] Replace placeholder content with my own about, experience and skills
- [ ] Add my CV as a downloadable PDF
- [ ] Choose my own colour scheme and fonts
- [ ] Add my current project to the "Currently building" section
- [ ] Write a section of the site myself, from scratch
- [ ] Add a projects page as my GitHub fills up

## Learning log

What I've changed and what I learned doing it. Newest first.

| Date | What I did | What I learned |
|------|-----------|----------------|
| Nov 2026 | Set up GitHub repo, Cloudflare deployment and custom domain | How a Git repo connects to hosting so pushes go live automatically |
