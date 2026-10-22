# Research Publications — Mrinmoy Chakraborty

A public catalogue for verified scholarly and technical outputs.

## What this repository is for
- Indexing your publication metadata and linking to original publisher pages.
- Hosting a GitHub Pages research website.
- Linking to authorised open versions and Zenodo records.
- Maintaining citation metadata and a transparent publication history.

## First setup
1. Create a **public** repository named `YOUR-GITHUB-USERNAME.github.io`.
2. Upload `index.html` and `publications.csv` to the repository root.
3. In repository **Settings → Pages**, select deployment from the `main` branch and `/ (root)`.
4. Wait for deployment, then open `https://YOUR-GITHUB-USERNAME.github.io`.
5. Replace the example row in `publications.csv` with verified records. Keep a backup before editing.

## Publication record rules
- Use the exact published title and author order.
- Preserve the original DOI and publisher/proceedings link when available.
- Do not state an ISBN, DOI, indexing status, citation count or publisher unless verified.
- Link to a full-text PDF only when the licence, publisher policy or author agreement permits it.
- For a paper with no lawful public full text, keep its metadata and link to the publisher page.
- Do not upload confidential company documents, unpublished employer data, personal data, or third-party figures without permission.

## Suggested record workflow
1. Verify metadata against the publisher or official proceedings.
2. Add the record to `publications.csv`.
3. Check all links and author names.
4. Link an existing DOI; do not create a duplicate DOI for a published paper.
5. Deposit permitted manuscripts or supporting materials in an appropriate repository such as Zenodo.
6. Keep ORCID and Google Scholar profiles aligned with the verified record.

## Zenodo integration
Use Zenodo's GitHub integration for versioned research assets such as code, data, methods, and supplementary materials. A Zenodo DOI for a repository release identifies that archived release; it does **not** replace a journal article's DOI or make an unreviewed upload a formally published paper. For full-paper deposits, check the publisher's self-archiving policy and choose the permitted version.

## Licence
Do not apply an open licence to publisher-owned PDFs or third-party content unless you have authority to do so. Choose a licence separately for original website text, code, and datasets only after deciding what reuse you permit. Copyright remains with its respective owner.

## Google Scholar
This site is a discovery catalogue, not a guarantee of Google Scholar indexing. Google Scholar has specific technical requirements for individual papers, metadata and crawlable URLs. Keep original publisher/repository links and complete bibliographic details; monitor indexing rather than claiming it is guaranteed.

## Files
- `index.html` — responsive research catalogue.
- `publications.csv` — publication metadata table.
- `CITATION.cff` — citation metadata for this repository itself; customise before release.
