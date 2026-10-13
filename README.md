# Nilesh Shinde — academic website

Plain HTML + CSS. No build step. Hosted free on GitHub Pages.

## Put it online (one time, ~10 minutes)

1. Sign in to GitHub as **n-nshinde**.
2. Click **+ → New repository**. Name it exactly `n-nshinde.github.io`. Set it to **Public**. Click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in every file from this folder (unzip first). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder **/ (root)**. Save.
5. After 1–2 minutes your site is live at **https://n-nshinde.github.io**.

## Add your files

- **CV:** upload your CV named `cv.pdf` (the "CV ↓" button links to it).
- **Photo:** create a folder `images/`, upload `photo.jpg`, then in `index.html` replace
  `<div class="ph" role="img" aria-label="Photo placeholder">[YOUR PHOTO]</div>`
  with `<img src="images/photo.jpg" alt="Nilesh Shinde">`.
- **Paper figures:** in `research.html`, replace a `<div class="fig ph" ...>[MAP]</div>` with
  `<div class="fig"><img src="images/pnas2023.png" alt=""></div>`.

## Paper PDFs

Upload PDFs into the `papers/` folder using these exact names, and the buttons on the Research page will work:

| Paper | File name |
|---|---|
| JEEM — Land Registration and Conflict | papers/jeem-land-registration.pdf |
| Health Affairs Scholar — Primary Care & Weather | papers/has-primary-care-weather.pdf |
| EDE — Snowpack & Winter Wheat | papers/ede-snowpack-wheat.pdf |
| JEEM 2025 — Beyond the Canopy | papers/jeem2025-beyond-the-canopy.pdf |
| FPE 2024 — Tree Plantations | papers/fpe2024-tree-plantations.pdf |
| PNAS 2023 — Collective Property Rights | papers/pnas2023-collective-property-rights.pdf |
| R&R JDE — Irrigation & Groundwater Recharge | papers/rr-irrigation-groundwater-recharge.pdf |
| R&R World Dev — Command-and-Control | papers/rr-groundwater-command-and-control.pdf |
| WP — Water Pollution Damages | papers/wp-water-pollution-damages.pdf |
| WP — Clearing to Claim | papers/wp-clearing-to-claim.pdf |
| WP — Drought-Induced Deforestation | papers/wp-drought-deforestation.pdf |
| WP — Compliance & Stock Persistence | papers/wp-compliance-stock-persistence.pdf |
| WP — Local Governance in Brazil | papers/wp-local-governance-brazil.pdf |
| WP — Forest Disease & Wildfire | papers/wp-forest-disease-wildfire.pdf |
| WP — Agrarian Cost of Groundwater | papers/wp-groundwater-agrarian-cost.pdf |
| WP — Drought & Judicial Outcomes | papers/wp-drought-judicial-outcomes.pdf |
| WP — Superfund & Soil Chemistry | papers/wp-superfund-soil-chemistry.pdf |

Not ready to share a draft yet? Delete that paper's Draft button (or change it to `href="mailto:nnshinde@iu.edu"` and text "Request").

For published papers, check each journal's sharing policy (most allow posting the accepted manuscript; PNAS and Elsevier journals have author-sharing rules). Each PDF must be under 25 MB to upload in the browser.

## Edit later

On GitHub, open any file → pencil icon → edit → **Commit changes**. The site updates in about a minute.

- New paper: copy an `<article ...>` block in `research.html` and change the text. `data-theme` is `land`, `water` or `climate`.
- Text in square brackets like `[Course title]` is a placeholder to fill in or delete.

## Optional: custom domain

Buy a domain (e.g., nileshshinde.com, ~$12/yr), then GitHub **Settings → Pages → Custom domain** and follow the DNS instructions shown there.

## Files

| File | Page |
|---|---|
| index.html | Home |
| research.html | Research (theme filters, abstracts) |
| data-code.html | Data & Code |
| teaching.html | Teaching + prospective students |
| workshop.html | Social Cost of Water Pollution Workshop |
| resources.html | Resources |
| style.css | All styling (IU crimson #990000, cream #EDEBEB) |
