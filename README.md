# SafeAV Research website

A responsive multi-page research website with a homepage, project catalog, dedicated safety-study page, publications, and about page. No build tools or external packages are required.

## Preview

Open `index.html` in a browser, or serve this folder with a local static server.

## Publish on GitHub Pages

1. Create a GitHub repository, such as `safeav-research`.
2. Upload all website files and folders to the repository root, preserving `assets/`, `research/`, `publications/`, and `about/`. Upload `.nojekyll` too. Do not upload the ZIP as the website.
3. In **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/(root)**.
4. GitHub will provide the published URL after deployment. A project repository normally appears at `https://YOUR-USERNAME.github.io/safeav-research/`.

For a personal root site, name the repository `YOUR-USERNAME.github.io` instead.

## Content and future updates

The website reflects the September 2026 project-task plan: two hazards, Behavior Agent and SimLingo, six planned conditions, Town12 development, and a four-week schedule. Results are explicitly pending. The interactive demo is illustrative, not empirical evidence.

Update the results section with measured results, denominators, confidence intervals, and experiment configurations when available. Add repository and paper links only after those resources exist. Keep future directions separate from demonstrated findings.

No analytics, tracking, backend, remote fonts, or private document links are included.

## Site structure

- `index.html`: research overview and featured study
- `research/index.html`: project catalog with topic filters
- `research/calibrated-safety/index.html`: study protocol and interactive safety demo
- `publications/index.html`: publication status and background resources
- `about/index.html`: research direction and principles
- `world-models-vla/index.html`: dated review of seven methods, primary sources, and evaluation distinctions. Include this folder when uploading to GitHub Pages.
- `assets/`: shared styles and favicon

All local links are relative for GitHub Pages project-path compatibility. Add future projects as folders under `research/` and add cards to the catalog and homepage. Results are explicitly pending. No contact details or institutional affiliations are invented.
