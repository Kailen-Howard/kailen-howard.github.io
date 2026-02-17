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

