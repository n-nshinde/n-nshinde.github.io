# Nilesh Shinde — academic website

Plain HTML + CSS. No build step. Hosted free on GitHub Pages.

## Put it online (one time, ~10 minutes)

1. Sign in to GitHub as **n-nshinde**.
2. Click **+ → New repository**. Name it exactly `n-nshinde.github.io`. Set it to **Public**. Click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in everything inside this folder, including the `papers`, `images`, `syllabi` and `data` folders. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder **/ (root)**. Save.
5. After 1–2 minutes your site is live at **https://n-nshinde.github.io**.

## Files on the site

- **Photo:** `images/shinde.jpg`.
- **Syllabus:** `syllabi/e340-syllabus.pdf`.
- **Paper PDFs** live in `papers/`, named `venueYEAR-short-title.pdf` for published papers, `rr-short-title.pdf` for revise-and-resubmits and `wp-short-title.pdf` for working papers:

| Paper | File |
|---|---|
| JEEM 2027 — Land Registration and Conflict (publisher PDF, not linked) | papers/jeem2026-land-registration-conflict.pdf |
| EDE 2026 — Snowpack and Winter Wheat (publisher PDF, not linked) | papers/ede2026-snowpack-winter-wheat.pdf |
| JEEM 2025 — Beyond the Canopy | papers/jeem2025-beyond-the-canopy.pdf |
| PNAS 2023 — Collective Property Rights | papers/pnas2023-collective-property-rights.pdf |
| Health Affairs Scholar 2026 — Primary Care and Weather | papers/has2026-primary-care-weather.pdf |
| FPE 2024 — Tree Plantations in Sub-Saharan Africa | papers/fpe2024-tree-plantations.pdf |
| Book chapter 2022 — Tree Cover in Andhra Pradesh | papers/chapter2022-tree-cover-andhra-pradesh.pdf |
| R&R JDE — Irrigation and Groundwater Recharge | papers/rr-irrigation-groundwater-recharge.pdf |
| WP — Gross External Damages of Water Pollution | papers/wp-water-pollution-damages.pdf |
| WP — Clearing to Claim (RCI WP 14) | papers/wp-clearing-to-claim.pdf |
| WP — Local Governance in Brazil | papers/wp-local-governance-brazil.pdf |
| WP — Drought-Induced Deforestation | papers/wp-drought-deforestation.pdf |

Papers without a PDF show an "Email me for draft" link instead ("Email me for a copy" for the two non-open-access published papers). To post a draft later, put the PDF in `papers/` and change that link to `<a href="papers/wp-short-title.pdf">Working paper draft</a>`.

Each PDF must be under 25 MB to upload in the browser. Compress large PDFs before uploading (downsample images to ~150 dpi); the current files are all under 5 MB (the two newest were compressed to 150 dpi on 2026-10-27).

For published papers, check each journal's sharing policy: Elsevier (JEEM, Forest Policy and Economics) and Cambridge (EDE) usually allow only the accepted manuscript on a personal site. The "Downloaded from … Indiana University" stamps were removed from the PNAS and Health Affairs Scholar PDFs; strip them from any new library download before posting.

## Update the live site

Upload the changed files with **Add file → Upload files** (same names replace the old ones), then wait 1–2 minutes and hard-refresh with **Cmd + Shift + R**.

Every page loads `style.css?v=6`. After changing `style.css`, bump the number (`?v=7`, …) in all six HTML files so browsers fetch the new styles.

## Edit later

On GitHub, open any file → pencil icon → edit → **Commit changes**. The site updates in about a minute.

- New paper: copy one `<li>` in `research.html` and change the text. Format: title, then "(with coauthors) Year. *Journal*, volume: pages." and the links. If it is recent, also update "Recent papers" in `index.html`.
- New course: copy one `<article class="row">` in `teaching.html`.
- Titles, coauthor order and years follow the journal record (Crossref/DOI) for published papers and the CV for working papers. Keep `index.html` and `research.html` consistent.
- New paper also goes under its country in `map.html` (copy one `<li>` and set its topic label: Land, Forests, Water, Climate, Health or Pollution). A new country: add a `<section>` there and its 3-letter code to `REGIONS` in the script at the bottom.

## Repository visibility

GitHub Pages on the free plan needs a public repo. A private repo with a public site needs GitHub Pro. Everything in the repo is already public through the site, so keeping it public is fine.

## Optional: custom domain

Buy a domain (e.g., nileshshinde.com, ~$12/yr), then GitHub **Settings → Pages → Custom domain** and follow the DNS instructions shown there.

## Files

| File | Page |
|---|---|
| index.html | Home |
| research.html | Research: journal articles, book chapters, working papers |
| map.html | Research Map: countries highlighted, papers listed by country (uses data/countries.geojson, Natural Earth) |
| teaching.html | Teaching |
| workshop.html | Community: Social Cost of Water Pollution Workshop, Dhar India Studies Program, CLACS |
| resources.html | Students: working with me + getting started in research (four steps that expand on click; each is a `<details>` block) |
| style.css | All styling (IU crimson #990000 accent on white) |
| data/countries.geojson | Country outlines for the Research Map (Natural Earth, public domain) |

## Sharing published papers

- **Open access (CC BY / CC BY-NC-ND):** post the publisher PDF, labelled "PDF (open access)". This covers PNAS 2023, Health Affairs Scholar 2026 and JEEM 2025.
- **Not open access (Elsevier JEEM 2027, Cambridge EDE 2026):** the site shows "Email me for a copy" + DOI (sending a copy to individual colleagues and students is allowed). Their publisher PDFs are in `papers/` for your own reference but are not linked; anything uploaded to this public repo can be downloaded by anyone, so leave them out of uploads to keep them private. To post them properly, use your accepted manuscript (the final version after peer review, before typesetting) with a cover page, labelled "Author manuscript". For EDE you can also add a free Cambridge Core Share link (article page → Share).
- **Author manuscripts already posted:** FPE 2024 and the Routledge chapter. Each has a cover page with the citation, DOI link and required licence/notice text (Elsevier: CC BY-NC-ND 4.0; Routledge: "Accepted Manuscript of a book chapter published by Routledge…"). Add the same kind of cover page to future accepted manuscripts.
- **Working papers:** labelled "Working paper draft".
