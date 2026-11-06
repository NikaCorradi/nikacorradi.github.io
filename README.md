# Personal academic website (Quarto)

## Pages
- `index.qmd`: Home (bio, News, contact) · `photo.jpg`: your portrait
- `research.qmd`, `teaching.qmd`, `reading.qmd`, `photography.qmd` (+ `photos/`)
- `_quarto.yml`: menu and links · `styles.css`: look

## Editing (no software needed)
1. On GitHub, open the `.qmd` file, click the pencil icon.
2. Change the text, click **Commit changes**.
3. GitHub rebuilds the site automatically (tab **Actions**); live in 2–3 minutes.

## Adding a news item (top of the News block in index.qmd)
```
[Mon YYYY]{.news-date}
[**Short title.** One sentence.]{.news-text}
```

## Adding a photo
Upload the image into `photos/` (Add file → Upload files), then add a line to `photography.qmd`:
`![Building, City, Year](photos/file-name.jpg){group="arch"}`
