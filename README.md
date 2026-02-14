# 🌐 vrragu.com

Personal website and blog built with [Astro](https://astro.build/) and [Tailwind CSS](https://tailwindcss.com/).

Live at [www.vrragu.com](https://www.vrragu.com)

## 🛠 Stack

- Astro (static site generator)
- Tailwind CSS v4
- Astro Content Collections (markdown blog)
- GitHub Pages + GitHub Actions (deployment)

## 🚀 Development

```sh
npm install
npm run dev
```

## ✍️ Adding a blog post

Create a new `.md` file in `src/content/blog/`:

```md
---
title: "Your Post Title"
description: "A short description"
pubDate: 2026-02-14
tags: ["tag1", "tag2"]
---

Your content here.
```

## 📦 Build & Deploy

Pushes to `main` trigger a GitHub Actions workflow that builds and deploys to GitHub Pages automatically.

```sh
npm run build    # local build to ./dist/
npm run preview  # preview the build
```
