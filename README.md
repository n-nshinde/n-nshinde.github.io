# Nilesh Shinde — academic website

Plain HTML + CSS. No build step. Hosted free on GitHub Pages.

## Put it online (one time, ~10 minutes)

1. Sign in to GitHub as **n-nshinde**.
2. Click **+ → New repository**. Name it exactly `n-nshinde.github.io`. Set it to **Public**. Click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in everything inside this folder, including the `papers`, `images` and `syllabi` folders. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder **/ (root)**. Save.
5. After 1–2 minutes your site is live at **https://n-nshinde.github.io**.

## Files on the site

- **Photo:** `images/shinde.jpg`.
- **Syllabus:** `syllabi/e340-syllabus.pdf`.
- **Paper PDFs** live in `papers/`, named `venueYEAR-short-title.pdf` for published papers, `rr-short-title.pdf` for revise-and-resubmits and `wp-short-title.pdf` for working papers:

| Paper | File |
|---|---|
| JEEM 2027 — Land Registration and Conflict Reduction | papers/jeem2026-land-registration.pdf |
| JEEM 2025 — Beyond the Canopy | papers/jeem2025-beyond-the-canopy.pdf |
| FPE 2024 — Tree Plantations in Sub-Saharan Africa | papers/fpe2024-tree-plantations.pdf |
| Book chapter 2022 — Tree Cover in Andhra Pradesh | papers/chapter2022-tree-cover-andhra-pradesh.pdf |
| R&R JDE — Irrigation and Groundwater Recharge | papers/rr-irrigation-groundwater-recharge.pdf |
| WP — Gross External Damages of Water Pollution | papers/wp-water-pollution-damages.pdf |
| WP — Clearing to Claim (RCI WP 14) | papers/wp-clearing-to-claim.pdf |
| WP — Local Governance in Brazil | papers/wp-local-governance-brazil.pdf |
| WP — Drought-Induced Deforestation | papers/wp-drought-deforestation.pdf |

Papers without a PDF show an "Email me for draft" link instead. To post a draft later, put the PDF in `papers/` and change that link to `<a href="papers/wp-short-title.pdf">Draft</a>`.

Each PDF must be under 25 MB to upload in the browser. Compress large PDFs before uploading (downsample images to ~150 dpi); the current files are all under 4 MB.

For published papers, check each journal's sharing policy: Elsevier (JEEM, Forest Policy and Economics) and Cambridge (EDE) usually allow only the accepted manuscript on a personal site. The PNAS, EDE and Health Affairs Scholar PDFs still carry a "Downloaded from … Indiana University" line on each page.

## Update the live site

Upload the changed files with **Add file → Upload files** (same names replace the old ones), then wait 1–2 minutes and hard-refresh with **Cmd + Shift + R**.

Every page loads `style.css?v=2`. After changing `style.css`, bump the number (`?v=3`, …) in all five HTML files so browsers fetch the new styles.

## Edit later

On GitHub, open any file → pencil icon → edit → **Commit changes**. The site updates in about a minute.

- New paper: copy one `<li>` in `research.html` and change the text. Format: title, then "(with coauthors) Year. *Journal*, volume: pages." and the links. If it is recent, also update "Recent papers" in `index.html`.
- New course: copy one `<article class="row">` in `teaching.html`.
- Titles, coauthor order and years follow the journal record (Crossref/DOI) for published papers and the CV for working papers. Keep `index.html` and `research.html` consistent.

## Repository visibility

GitHub Pages on the free plan needs a public repo. A private repo with a public site needs GitHub Pro. Everything in the repo is already public through the site, so keeping it public is fine.

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
