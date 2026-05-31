---
title: "This Website"
description: "Personal site built with Astro, deployed to GitHub Pages on a custom domain."
date: 2026-05-31
tech: ["Astro", "TypeScript", "GitHub Pages"]
github: "https://github.com/dileepkonidela/dileep-website"
featured: true
---

A minimal personal site for writing, projects, and experiments.

## Stack

- **Astro** — static site generator with first-class Markdown support
- **TypeScript** — content collection schemas and type-safe components
- **GitHub Actions** — automated builds and deploys on push to main
- **GitHub Pages** — free hosting with custom domain

## How to add a project

Create a new `.md` file in `src/content/projects/`. The frontmatter:

```yaml
---
title: "Project name"
description: "One sentence."
date: 2026-06-01
tech: ["Rust", "PostgreSQL"]
url: "https://example.com"
github: "https://github.com/you/repo"
featured: false
---
```
