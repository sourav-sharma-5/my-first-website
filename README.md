# Sourav's Thoughts

A minimal static blog. No frameworks, no build tools, no dependencies.

## How to Add a New Entry

1. Open `index.html`
2. Find the `NEW ENTRY TEMPLATE` comment at the top of `<main>`
3. Copy the `<article>` block from the comment
4. Paste it right below the comment (before all existing entries)
5. Fill in the title, date, and your content
6. Save

Optionally update `feed.xml` with a matching `<item>` block (same copy-paste pattern).

## How to Deploy

```bash
git add -A && git commit -m "Week of Feb 20" && git push
```

The site auto-deploys via GitHub Pages on push to `main`.

## File Structure

- `index.html` — The entire blog (all entries)
- `style.css` — All styles
- `feed.xml` — RSS feed
- `README.md` — This file
