# The Hub - AB

My personal website: who I am, my CV, where to find me, and the projects I'm working on.

**WIP Live site:** [abbybrazell.com](https://www.abbybrazell.com)

I'm a Decision Support Analyst moving further into data and analytics. This site is my home base for that, and it's also a hands-on way for me to learn web development.

## How this was built

The first version of this site was generated with an AI assistant (Claude), from a brief I wrote: a simple, clean page with my CV, an about section and my links.

From there, the site is mine to own. I'm editing the content, making the design decisions, and gradually rewriting and extending the code myself so I understand every part of it. The [learning log](#learning-log) below tracks what I've changed and what I've learned along the way.

## Tech

- **HTML and CSS only.** No framework and no build step, so every file is readable and easy to change.
- **Hosting:** Cloudflare Pages, connected to this repo. Every push to `main` deploys automatically, and only the `public/` folder is published to the site.
- **Domain:** managed through Cloudflare DNS.

## Project structure

```
public/           everything in here is published to abbybrazell.com
  index.html      the page content
  styles.css      layout, colours and fonts (theme variables at the top)
  404.html        shown for pages that don't exist
  cv.pdf          my CV
LICENSE           MIT licence for the code
README.md         this file (stays on GitHub, not published)
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

## Licence

The code (HTML and CSS) is available under the [MIT License](LICENSE).

The content (including my CV, bio, writing and images) is © Abby Brazell. All rights reserved. Please don't reuse it without asking.

## Learning log

What I've changed and what I learned doing it. Newest first.

| Date | What I did | What I learned |
|------|-----------|----------------|
| Nov 2026 | Set up GitHub repo, Cloudflare deployment and custom domain | How a Git repo connects to hosting so pushes go live automatically |
| Nov 2026 | Moved site files into `public/`, set Cloudflare's build output directory, removed unused config, added an MIT licence | Cloudflare publishes every file in the output folder, so separating website files from project files keeps the site clean. The difference between Cloudflare Pages and Workers settings. |
