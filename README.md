# KailenHoward Blog

Minimal, static Astro blog optimized for readability and speed.

## Stack

- Astro (`output: "static"`)
- Markdown/MDX content in `src/content/posts`
- RSS via `@astrojs/rss`
- Sitemap via `@astrojs/sitemap`

## Run locally

```bash
npm install
npm run dev
```

Then open `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

1. Push this project to the `main` branch of `kailen-howard.github.io`.
2. In GitHub repo settings, set Pages source to `Deploy from a branch`.
3. Select branch `gh-pages` and folder `/ (root)`.
4. The workflow in `.github/workflows/deploy.yml` will build and publish `dist` to `gh-pages` on each push to `main`.

## Content

Add posts in `src/content/posts` using Markdown or MDX with frontmatter:

```md
---
title: "Post title"
description: "Short description"
pubDate: 2026-02-17
tags: ["frontend"]
draft: false
ogImage: "/og-default.svg"
---
```
