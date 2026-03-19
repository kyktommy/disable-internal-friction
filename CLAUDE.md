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

Each article must include three perspective sections, placed in this order after the main body:

**1. 阿德勒心理學 / Adlerian Psychology** — connects the article's theme to Adlerian concepts (e.g., separation of tasks, teleological behavior, courage to be imperfect, social interest, lifestyle).
- zh: `## 阿德勒心理學怎麼說`
- en: `## What Adlerian Psychology Says`

**2. 金剛經／心經 / Diamond Sutra & Heart Sutra** — connects the article's theme to Buddhist concepts from these two texts (e.g., 無所住、色即是空、心無罣礙、無所得、三心不可得、不住相).
- zh: `## 金剛經／心經怎麼說`
- en: `## What the Diamond Sutra and Heart Sutra Say`

**3. 易經 / I Ching** — connects the article's theme to a relevant hexagram and its Confucian commentary (彖傳／象傳). Choose the hexagram that best maps to the article's core dynamic.
- zh: `## 易經怎麼說`
- en: `## What the I Ching Says`

## Stack

- Hugo v0.157.0 + PaperMod theme
- Deploys to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`