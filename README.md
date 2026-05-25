# World Cup Analytics — presentation

Quarto Reveal.js slides for the **world_cup_analytics** Shiny project (~40 minutes).

## Render

```bash
cd /Users/rabin/Documents/courses/world_cup_analytics_presentation
quarto render index.qmd
quarto preview index.qmd   # live preview while editing
```

Output: `index.html` (gitignored; regenerate locally).

## Placeholders to fill

- `images/` — pipeline diagram, Shiny screenshots, World Cup H2H demo capture
- Speaker notes are in `::: {.notes}` blocks in `index.qmd`
- Trim upload-script chunk on the slide to ~8–12 lines when you rehearse

## Related repo

[/Users/rabin/Documents/courses/world_cup_analytics](../world_cup_analytics) — `app.R`, `data/international/`, `upload_international_results.R`
