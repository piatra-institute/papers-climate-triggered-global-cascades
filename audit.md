# Audit

## 2026-08-30 - Publication

Scope: public GitHub release and inclusion in the PIATRA papers index and
website.

Changes:

- Changed metadata status from `built` to `published` and regenerated the
  workspace papers index.
- Created the public
  `piatra-institute/papers-climate-triggered-global-cascades` repository with
  the standard PIATRA paper description, committed the complete package as
  `setup: initial commit`, and pushed `main`.
- Synced the final PDF to
  `public/papers/climate-triggered-global-cascades.pdf` and added the paper to
  the website under political science, economics, and biology, with the formal
  and essay kinds.

Verification:

- The synced website PDF is byte-identical to `paper/PAPER.pdf`.
- `papers check climate-triggered-global-cascades`: PASS, including the
  published-web gate.
- The PIATRA website production build compiled, type-checked, and generated all
  229 static pages, including `/papers`.
- The website lint command remains unavailable because the repository runs
  ESLint 10 with legacy configuration and no flat `eslint.config.*`; this is a
  pre-existing repository-tooling failure, not a paper-entry diagnostic.

## 2026-08-30 - Research, drafting, and built-paper verification

Scope: complete paper package from the seeded origin chat through the brief,
tiered research notes, frozen bibliography, manuscript, metadata, standalone
builder, and rendered PDF.

Changes:

- Recast the question as a model-specification problem and stated the central
  epistemic limit: no defensible published probability currently exists for a
  climate-caused billion-death year.
- Specified 1177-G as a stochastic hybrid causal model with temporal multilayer
  networks, buffers and recovery clocks, competing mortality hazards,
  state-dependent cascade diagnostics, rare-event sampling, and paired climate
  attribution ensembles.
- Separated transferable model architecture from non-transferable analogies in
  Bronze Age collapse and nuclear-winter food modeling.
- Froze 19 bibliography entries after publisher, DOI, or official-source checks.
  Verified the population and mortality scale calculations independently.
- Corrected two missing LaTeX backslashes found during visual QA and replaced
  long raw reference URLs with compact clickable locators. Vendored the
  canonical standalone builder.

Verification:

- `papers voice climate-triggered-global-cascades`: 0 errors, 0 review
  candidates; no rhythm flags, with 25% short sentences and sentence-length
  standard deviation 10.
- `papers refs climate-triggered-global-cascades`: 19 in-text citation keys, 19
  bibliography entries, 0 missing, 0 unused.
- `papers claims climate-triggered-global-cascades`: `claims_target: none`;
  numerical literature claims and threshold arithmetic received manual review.
- Independent arithmetic checks reproduced 3.34 deaths per 10,000 per day for
  the whole 8.2-billion reference population, 6.85 for a 4-billion exposed
  population, and about 599 million deaths at 2 per 10,000 per day for 365 days.
- Workspace build and `uv run build.py`: both passed. Final PDF is 14 letter-size
  pages with embedded, subsetted Unicode fonts.
- Visual QA: all 14 pages rendered to PNG and inspected for clipping, overlap,
  equations, missing glyphs, page furniture, and section transitions; no defects
  remained in the final render.
- `papers check climate-triggered-global-cascades`: PASS.
