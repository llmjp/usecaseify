# Changelog

All notable changes to this documentation repository are recorded here.

## 1.3.0 — 2026-07-13

### Changed

- Documented the live credit contract: 2 credits on sign-up, 1 credit for a
  delivered Discovery, and 1 credit for each GTM Pack generation or explicit
  regeneration
- Clarified reservation, delivery settlement, automatic release, and
  retry-idempotency behavior across Product facts, FAQ, and both `llms.txt`
  files
- Documented how explicit product-user choices and quality feedback are stored,
  the Settings-controlled UseCaseify-specific training eligibility, and the
  exclusion of account, payment, and Validation respondent data

## 1.2.0 — 2026-07-13

### Changed

- Synchronized Product facts, Methodology, FAQ, scoring guides, AI limitations,
  whitepapers, README, and both `llms.txt` files with the deployed three-way
  decision behavior: supported recommendation, explicitly labeled priority
  validation candidate, or no recommendation when guardrails are not met
- Clarified that a priority validation candidate is an early hypothesis to
  test, not validated demand or a guaranteed market outcome
- Re-reviewed current beta counts and pricing against the deployed product
- Refreshed sitemap modification dates for the site-wide public-content audit

## 1.1.0 — 2026-07-12

### Added

- English whitepaper v1.0 (`docs/en/whitepaper.md`)
- End-to-end example with a clearly-labeled fictional product (EN/JA)
- Guides: how to validate a use case, use case scoring framework (EN/JA)
- Comparison: UseCaseify vs ChatGPT (EN/JA)
- AI limitations pages (EN/JA)
- `SECURITY.md`
- Privacy and data overview pages (EN/JA), deferring to the official Privacy Policy
- Social preview image, Open Graph defaults, and EN⇄JA hreflang annotations
- SoftwareApplication structured data on the documentation home

### Changed

- Unified the product definition across README, index pages, product facts,
  FAQ, and llms.txt ("…decide which use case, audience, and value proposition
  to take to market — backed by traceable market evidence and feedback from
  real prospects")
- Product facts now carries an authority header and a source-hierarchy
  section; volatile counts are labeled as current beta implementation with a
  last-reviewed date
- FAQ expanded with seven functional questions (EN/JA, structured data kept
  in sync)
- README: added "What UseCaseify is not", trial call-to-action, links to the
  new pages, and a last-reviewed date
- Sitemap now lists all 23 pages

## 1.0.0 — 2026-07-12

### Added

- Repository README with the current product definition (English and Japanese)
- Product facts pages (`docs/en/product-facts.md`, `docs/ja/product-facts.md`)
- Methodology pages (`docs/en/methodology.md`, `docs/ja/methodology.md`)
- FAQ pages with FAQPage structured data (`docs/en/faq.md`, `docs/ja/faq.md`)
- Glossary pages (`docs/en/glossary.md`, `docs/ja/glossary.md`)
- Japanese whitepaper v1.0 (`docs/ja/whitepaper.md`)
- GitHub Pages structure (`docs/_config.yml`, index pages, 404)
- `docs/llms.txt`, `docs/robots.txt`, `docs/sitemap.xml`
- `CONTRIBUTING.md`, `COPYRIGHT.md`, `TRADEMARK.md`, `CITATION.cff`

### Notes

- This release documents UseCaseify as deployed in July 2026 (beta): the use case
  discovery and validation workflow described on [usecaseify.com](https://usecaseify.com/).
- The whitepaper is authored for this release (v1.0, 2026-07-12) and reflects the
  current product; it is not a republication of an earlier document.
