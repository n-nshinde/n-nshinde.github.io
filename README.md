# Nilesh Shinde — academic website

Plain HTML + CSS. No build step. Hosted free on GitHub Pages.

## Put it online (one time, ~10 minutes)

1. Sign in to GitHub as **n-nshinde**.
2. Click **+ → New repository**. Name it exactly `n-nshinde.github.io`. Set it to **Public**. Click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in every file from this folder (unzip first). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder **/ (root)**. Save.
5. After 1–2 minutes your site is live at **https://n-nshinde.github.io**.

## Files on the site

- **CV:** `cv.pdf` (linked from the menu and the Home page).
- **Photo:** `images/shinde.jpg`.
- **Syllabus:** `syllabi/e340-fall2026-syllabus.pdf`.
- **Paper PDFs** live in `papers/`, named `venueYEAR-short-title.pdf` for published papers, `rr-short-title.pdf` for revise-and-resubmits and `wp-short-title.pdf` for working papers:

| Paper | File |
|---|---|
| JEEM 2027 — Land Registration and Conflict Reduction | papers/jeem2026-land-registration.pdf |
| Health Affairs Scholar 2026 — Primary Care and Weather | papers/has2026-primary-care-weather.pdf |
| EDE 2026 — The Cold, Hard Truth (snowpack) | papers/ede2026-snowpack-wheat.pdf |
| JEEM 2025 — Beyond the Canopy | papers/jeem2025-beyond-the-canopy.pdf |
| FPE 2024 — Tree Plantations in Sub-Saharan Africa | papers/fpe2024-tree-plantations.pdf |
| PNAS 2023 — Collective Property Rights | papers/pnas2023-collective-property-rights.pdf |
| Book chapter 2022 — Tree Cover in Andhra Pradesh | papers/chapter2022-tree-cover-andhra-pradesh.pdf |
| R&R JDE — Irrigation and Groundwater Recharge | papers/rr-irrigation-groundwater-recharge.pdf |
| WP — Gross External Damages of Water Pollution | papers/wp-water-pollution-damages.pdf |
| WP — Local Governance in Brazil | papers/wp-local-governance-brazil.pdf |
| WP — Drought-Induced Deforestation | papers/wp-drought-deforestation.pdf |

Papers without a PDF show an "Email me for draft" link instead. To post a draft later, put the PDF in `papers/` and change that link to `<a href="papers/wp-short-title.pdf">Draft</a>`.

For published papers, check each journal's sharing policy (most allow posting the accepted manuscript). Each PDF must be under 25 MB to upload in the browser.

## Edit later

On GitHub, open any file → pencil icon → edit → **Commit changes**. The site updates in about a minute.

- New paper: copy one `<li>` in `research.html` and change the text. Format: title, then "(with coauthors) Year. *Journal*, volume: pages." and the links. If it is recent, also update "Recent papers" in `index.html`.
- New course: copy one `<article class="row">` in `teaching.html`.

## Optional: custom domain

Buy a domain (e.g., nileshshinde.com, ~$12/yr), then GitHub **Settings → Pages → Custom domain** and follow the DNS instructions shown there.

## Files

| File | Page |
|---|---|
| index.html | Home |
| research.html | Research: journal articles, book chapters, working papers |
| teaching.html | Teaching |
| workshop.html | Social Cost of Water Pollution Workshop |
| resources.html | Students: working with me + getting started in research |
| style.css | All styling (IU crimson #990000 accent on white) |
