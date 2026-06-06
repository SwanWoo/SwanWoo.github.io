# SwanWoo.github.io

Personal portfolio & blog, built with [Astro](https://astro.build/) and deployed to GitHub Pages.

🌐 **https://swanwoo.github.io**

## Tech Stack

- **Framework**: Astro 5 (static output)
- **Content**: MDX via `@astrojs/mdx`
- **Deployment**: GitHub Actions → GitHub Pages
- **Styling**: Inline CSS (dark theme, responsive)

## Project Structure

```
├── src/
│   ├── content/          # Content collections
│   │   ├── config.ts     # Schema definitions (portfolio, blog)
│   │   ├── blog/         # Blog posts (.mdx)
│   │   └── portfolio/    # Portfolio projects (.mdx)
│   ├── layouts/
│   │   └── Layout.astro  # Base HTML layout
│   └── pages/
│       ├── index.astro   # Home page
│       ├── cv.astro      # CV / Resume
│       ├── blog/         # Blog listing & detail pages
│       └── portfolio/    # Portfolio listing & detail pages
├── public/               # Static assets
└── .github/workflows/
    └── deploy.yml        # CI/CD pipeline
```

## Local Development

Requires **Node.js 18+** and **npm**.

```bash
npm install       # Install dependencies
npm run dev       # Start dev server (localhost:4321)
npm run build     # Build to ./dist
npm run preview   # Preview production build
```

## Deployment

Automatically deploys to GitHub Pages on push to `master` via GitHub Actions.

Manual trigger: **Actions → Deploy Astro to GitHub Pages → Run workflow**.

## Adding Content

### Portfolio Project

Create `src/content/portfolio/my-project.mdx`:

```mdx
---
title: "Project Name"
description: "Short description"
tags: ["tag1", "tag2"]
order: 1
---

Project details in MDX...
```

### Blog Post

Create `src/content/blog/2026-01-01-my-post.mdx`:

```mdx
---
title: "Post Title"
date: 2026-01-01
tags: ["tag1"]
---

Post content in MDX...
```

## License

MIT
