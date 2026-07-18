# Kristofor Figueiredo - Portfolio

Personal portfolio for Kristofor Figueiredo, focused on business analytics, technology sourcing, supply chain, sports analytics, and applied machine learning.

The site includes a downloadable résumé, locally hosted profile photography, verified employer logos, an interactive global work map, technical case studies, and links to live project demonstrations and source repositories.

**Live site:** https://krisfigueiredo-ui.github.io/

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://127.0.0.1:8000/`.

## Content and privacy

The site is based on the owner-provided résumé and verified public LinkedIn experience. It intentionally excludes confidential client work, unpublished source data, private contact details, proprietary deliverables, and the University of Miami baseball dashboard. Team projects name the classmates credited in the source project materials.

The banking and inventory-planning dashboards are synthetic portfolio demonstrations. Their records, KPIs, SQL, and DAX examples are fictional and do not reproduce client systems, data, reports, or NDA-covered deliverables.

## Portfolio structure

- `index.html` — résumé, experience, interactive work map, selected projects, and employer/client context
- `projects.html` — methods-first case studies covering model design, validation, limitations, and team credit
- `cnb-synthetic-dashboard.html` — fictional banking portfolio/risk and DAX demonstration
- `tractor-synthetic-inventory.html` — fictional SKU planning and inventory-policy demonstration
- `assets/Kristofor_Figueiredo_Resume.pdf` — downloadable résumé

## Attribution

The blank world map is the CC0 [`WorldMap-Blank-Noborders.svg`](https://commons.wikimedia.org/wiki/File:WorldMap-Blank-Noborders.svg) from Wikimedia Commons. Employer and client marks identify publicly documented work or engagement context; all trademarks belong to their respective owners.

## Stack

- Semantic HTML
- Responsive CSS
- Locally hosted image and document assets
- Open Graph metadata for social sharing
- No framework, tracking, external font, or build dependency
- GitHub Pages deployment through Actions
