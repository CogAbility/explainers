# CogAbility Explainers

Public GitHub Pages site (Pages source: `main`, root) for short interactive explainers.

## Layout
- `index.html`: landing page, rendered from `explainers.json`
- `explainers.json`: one entry per explainer: `slug`, `title`, `ticket` (URL), `date` (YYYY-MM-DD), `summary`
- `<ticket>-<slug>/index.html`: one self-contained page per explainer (inline CSS/JS/images)
- `assets/`: optional shared CSS

## Adding an explainer
1. Create `<ticket>-<slug>/index.html`.
2. Add an entry to `explainers.json`.
3. Run the privacy check below, then commit to `main`.

## Privacy rule (this repo is PUBLIC)
Never include student names or other PII, secrets/tokens/keys, internal URLs (Cloudant, Jenkins, ArgoCD, internal hosts), call IDs, or non-public phone numbers. Public department lines (e.g. county phone numbers) are OK. Use aggregate counts only.
