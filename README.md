# yarong-research-data

Public stock-research records shown on https://yarong.kr/research/. Data only; no site code.

- `research-export.json` — latest public export from the research server (read-only export, public fields only).
  Pushed with a deploy key that is registered on this repository only.
- `src/content/research/*.json`, `src/content/performance/*.json` — the published records, merged by
  `.github/workflows/merge.yml` with the site's importer. Published pre-market records are never replaced.

The site builds from this repository on every deploy (see `docs/research-auto-publish.md` in the site repository).
Personal research records; not investment advice.
