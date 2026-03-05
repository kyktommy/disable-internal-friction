It is a Hugo blog about how to disable your internal friction.

I will give you a topic / article for you to elaborate.

## Article structure

Hugo multilingual site. Articles go in:
- `content/en/posts/<slug>.md` — English
- `content/zh/posts/<slug>.md` — Chinese

Use a concise kebab-case slug (e.g. `challenge-not-drain`).

Always write both language versions whenever you create or update either one.

Each article needs Hugo front matter:
```
---
title: ""
date: YYYY-MM-DD
description: ""
tags: []
showToc: true
---
```

## Stack

- Hugo v0.157.0 + PaperMod theme
- Deploys to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`