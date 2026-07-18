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

The IT asset-risk page accompanies a University of Miami M.S. in Business Analytics capstone. The inventory-planning page accompanies a West Virginia University B.S.B.A. Supply Chain Management capstone. Their demonstration records, public metrics, and DAX examples were created for the portfolio and do not reproduce client systems, source data, or proprietary deliverables.

## Portfolio structure

- `index.html` — résumé, experience, interactive work map, selected projects, and employer/client context
- `projects.html` — methods-first case studies covering model design, validation, limitations, and team credit
- `cnb-synthetic-dashboard.html` — confidentiality-safe IT asset lifecycle and risk capstone case study
- `tractor-synthetic-inventory.html` — fictional SKU planning and inventory-policy demonstration
- `assets/Kristofor_Figueiredo_Resume.pdf` — downloadable résumé

## Attribution

The blank world map is the CC0 [`WorldMap-Blank-Noborders.svg`](https://commons.wikimedia.org/wiki/File:WorldMap-Blank-Noborders.svg) from Wikimedia Commons. The Tractor wordmark is served from the company's official website asset. Employer, school, and capstone-partner marks identify publicly documented experience; all trademarks belong to their respective owners.

## Stack

- Semantic HTML
- Responsive CSS
- Locally hosted image and document assets
- Open Graph metadata for social sharing
- No framework, tracking, external font, or build dependency
- GitHub Pages deployment through Actions
