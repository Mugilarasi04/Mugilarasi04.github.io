# Portfolio — Mugilarasi M S

A real, static portfolio website (HTML/CSS/JS, no build step) — dark theme, hero with stats bar,
tabbed code snippets, project cards, achievements, and a connect section. Free to host on GitHub Pages.

## Files

```
index.html
css/style.css
js/script.js
assets/resume.pdf      ← your resume, linked from the Resume buttons
assets/favicon.svg
```

## Deploy on GitHub Pages (free)

1. Create a new GitHub repo. For a URL like `mugilarasi04.github.io`, name the repo exactly
   `Mugilarasi04.github.io` (must match your username). Any other name works too, it'll just live
   at `mugilarasi04.github.io/repo-name` instead.
2. Push all these files to the repo's root (keep the folder structure as-is).
3. In the repo, go to **Settings → Pages**, set Source to the `main` branch, root folder, save.
4. Your site goes live in a minute or two at the URL GitHub shows you there.

## Editing content

- All text lives directly in `index.html` — search for the section you want (About, Projects,
  Achievements, etc.) and edit in place.
- Colors and spacing live in `css/style.css` under `:root` at the top (`--accent` is the green,
  change it there to re-theme the whole site).
- To feature real LinkedIn posts: open the post on LinkedIn → **···** menu → **Embed this post** →
  copy the snippet → paste it inside `<div id="linkedin-embeds">` in `index.html`.
