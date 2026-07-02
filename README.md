# Chinese History Illustration

A static GitHub Pages site for a Traditional Chinese children's introduction to pre-Xia Chinese history.

## Site

- Live GitHub Pages URL: <https://plagenticclaw.github.io/chinese-history-illustration/>
- Entry page: `index.html`
- Styles: `assets/styles.css`
- Small navigation script: `assets/app.js`
- Source article: `pre-xia-era-chinese-history.md`
- Accuracy audit: `HISTORICAL_ACCURACY_REVIEW.md`

## Historical accuracy policy

The visual assets are children’s schematic learning aids, not precise maps, portraits, site plans, or full artifact reconstructions. Revision rule: prefer approximate regions over exact dots, motifs over invented portraits, and evidence-specific artifact forms over generic icons. Keep uncertainty visible, especially for legendary figures and the Erlitou/Xia question.

Current accuracy pass:

- `culture-map.svg` uses fuzzy regions for broad cultures and a site marker for Erlitou.
- `legend-characters.svg` uses motif cards, not invented faces or clothing.
- `farming-shift.svg` distinguishes millet/dry farming and rice/wet farming, with safer house types.
- `liangzhu-water-system.svg` is labelled as a concept diagram, not a site plan.
- `artifacts-chart.svg` uses more recognisable archaeological examples and softens interpretive claims.

## Local preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Publish with GitHub Pages

In GitHub:

1. Open **Settings → Pages**.
2. Set **Source** to **Deploy from a branch**.
3. Choose branch `main` and folder `/ (root)`.
4. Save.

The page will publish from the static files in this repository.
