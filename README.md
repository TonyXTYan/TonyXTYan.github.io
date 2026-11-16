# tonyxtyan.github.io

GitHub Pages user site, served at https://tonyxtyan.github.io/.

| Path | Purpose |
| --- | --- |
| `/` | Home |
| `/PencilMaps/` | PencilMaps app page, published from the PencilMaps repo's `site/` (GitHub Pages, Actions) |
| `/PencilMaps/support/` | App Store support URL |
| `/PencilMaps/privacy/` | App Store privacy policy URL |
| `/HeLab/` | Published from the HeLab repo's `gh-pages` branch |
| `/SRKit/` | The Relativistic Navigator, published from the SRKit repo (GitHub Pages, Actions) |

`404.html` sends any other casing of a project site's path (e.g. `/pencilmaps/privacy/`) to the right one, so the
paths work case-insensitively. Add a project to its `sites` list when it gets a site.

Plain static HTML; `.nojekyll` turns off Jekyll so a future `/.well-known/` folder (universal links) is served as-is.
