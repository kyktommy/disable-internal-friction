It is a Hugo blog about how to disable your internal friction.

I will give you a topic / article for you to elaborate.

## Article structure

Hugo multilingual site. Articles go in:
- `content/en/posts/<slug>.md` — English
- `content/zh/posts/<slug>.md` — Traditional Chinese

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

## Article content guidelines

Refine the provided topic into a compelling article title — make it specific, evocative, and aligned with the blog's theme of disabling internal friction. Use the refined title in the front matter.

Each article should include an **阿德勒心理學 / Adlerian Psychology** section that connects the article's theme to Adlerian concepts (e.g., separation of tasks, teleological behavior, courage to be imperfect, social interest, lifestyle). The section heading:
- zh: `## 阿德勒心理學怎麼說`
- en: `## What Adlerian Psychology Says`

## Stack

- Hugo v0.157.0 + PaperMod theme
- Deploys to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`