# LegalEase Decision Lab

Interactive product-management case study: save time without losing critical legal meaning. HTML, CSS, and vanilla JavaScript; no build, backend, or API key required.

Open `index.html` in a modern browser. Optional Google Fonts have system fallbacks. No documents are processed or user data persisted.

## Features

- Compare three handcrafted summaries of a fictional clause.
- Adjust strategy, scoring weights, and capacity.
- Select a release; inspect deferred work and proposed MVP gaps.
- Export a decision brief with rationale and unresolved gaps.
- Reset the exercise. Empty and over-capacity plans cannot export.

Score = weighted average benefit × confidence ÷ effort. Zero weights yield zero scores. Selecting an investment does not prove a release gate passed.

## GitHub Pages

1. Create a repository named `legalease-decision-lab`.
2. Upload this folder's contents to the repository root.
3. In Settings → Pages, choose Deploy from a branch, `main`, and `/ (root)`.
4. Open the deployment URL supplied by GitHub.

```sh
git init
git add .
git commit -m "Add LegalEase interactive decision lab"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/legalease-decision-lab.git
git push -u origin main
```

## Content provenance

Based on the shared LegalEase concept: plain-language AI summaries of legal documents for business customers. The supplied `01. LegalEase - Quick Summarize(1).pdf` was image-only and could not be extracted in this run. This is a concept-based adaptation, not a verified summary of the PDF. The central dilemma is an editorial interpretation. Clauses, scores, scenarios, capabilities, effort estimates, and release gates are illustrative, not actual LegalEase requirements or research findings.

Edit narrative in `index.html`, design in `styles.css`, and interactions in `app.js`. This is an educational prototype, not a working legal summarizer.
