# Personal academic website (Quarto)

## Files

- `_quarto.yml`: site settings, menu, links (ORCID, Scholar, LinkedIn)
- `index.qmd`: Home (bio, News, contact)
- `research.qmd`: dissertation, working papers, conferences
- `styles.css`: look and feel

Search for `TODO` and fill in or delete each one before publishing.

## Run locally

1. Install Quarto: https://quarto.org/docs/get-started/
2. In this folder: `quarto preview` (opens the site in the browser and reloads on save)
3. Build for publishing: `quarto render` (output goes to `docs/`)

In RStudio: File → Open Project in this folder, then the **Render** button.

## Publish free on GitHub Pages

1. Create a repository on GitHub, e.g. `USERNAME.github.io` (the site then lives at `https://USERNAME.github.io`).
2. Upload the folder contents, including `docs/` after `quarto render`.
3. Repository → Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/docs`.
4. Done in about a minute. For updates: edit the `.qmd`, run `quarto render`, push.

## Updating News

Add the newest item at the top of the News section in `index.qmd`:

```
**What happened** · *Month Year*\
One sentence of context.
```
