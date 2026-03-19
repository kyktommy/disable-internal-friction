It is a Hugo blog about how to disable your internal friction.

I will give you a topic / article for you to elaborate.

## Stack

- Hugo v0.157.0 + PaperMod theme
- Deploys to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`

## Article paths

Hugo multilingual site. Articles go in:
- `content/en/posts/<slug>.md` — English
- `content/zh/posts/<slug>.md` — Traditional Chinese

Use a concise kebab-case slug (e.g. `challenge-not-drain`).

Always write both language versions whenever you create or update either one.

## Skills

Use these skills when writing blog articles — they own all content guidelines:

| Task | Skill |
|---|---|
| Write a complete article (both languages, all sections) | `blog-writer` |
| Main article body | `blog-psychologist` |
| Adlerian Psychology section | `blog-adlerian` |
| Diamond Sutra & Heart Sutra section | `blog-sutra` |
| I Ching section | `blog-iching` |

`blog-writer` is the entry point — it invokes the other four in sequence and assembles the final Hugo files.

## Article section order

1. Main body (psychologist voice)
2. `## What Adlerian Psychology Says` / `## 阿德勒心理學怎麼說`
3. `## What the Diamond Sutra and Heart Sutra Say` / `## 金剛經／心經怎麼說`
4. `## What the I Ching Says` / `## 易經怎麼說`
5. `## Try This` / `## 試試這個` — 1–3 sentences, one concrete action for the reader
