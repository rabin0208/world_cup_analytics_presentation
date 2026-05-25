# World Cup Analytics — presentation

Quarto Reveal.js slides for the **world_cup_analytics** Shiny project (~40 minutes).

## View the slides

After rendering, open **`index.html`** locally or deploy it to GitHub Pages (see below).

```bash
quarto render index.qmd
open index.html
```

GitHub Pages must serve the **rendered** `index.html` and `index_files/` — not this README alone.

## Deploy to GitHub Pages

1. Render: `quarto render index.qmd`
2. Commit and push `index.html` and `index_files/` (they are tracked in git; only `.quarto/` is ignored)
3. Repo **Settings → Pages →** Deploy from branch **main**, folder **/ (root)**

Site URL: `https://rabin0208.github.io/world_cup_analytics_presentation/`

## Related repo

[World cup Analytics](https://github.com/rabin0208/world_cup_analytics) — `app.R`, `data/international/`, `upload_international_results.R`
