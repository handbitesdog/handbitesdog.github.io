# handbitesdog.com

The site itself. Served by GitHub Pages straight from the default branch — no
build step, no generator, so what is in the repo is what is on the web.

## What is here

| Path                             | Serves as                                     |
| -------------------------------- | --------------------------------------------- |
| `index.html`                     | `/`                                            |
| `footbag/ultrasuede-color-library/` | `/footbag/ultrasuede-color-library/`        |

`.nojekyll` turns off Jekyll processing. Nothing here needs it, and without the
file Pages would quietly skip any path beginning with an underscore.

## Ultrasuede Color Library

An archive of the Ultrasuede® LT colour range, rebuilt from colour cards and
Wayback captures of the mills' own swatch pages. Every path inside it is
relative, so the whole directory moves as a unit — it does not care that it
lives under `/footbag/`.

Its working repo, where the scraping and the research live, is
[handbitesdog/ultrasuede-color-library](https://github.com/handbitesdog/ultrasuede-color-library).
This copy is the published build; edits belong upstream and get copied down.

Ultrasuede® is a registered trademark of Toray. The archive is independent and
non-commercial.
