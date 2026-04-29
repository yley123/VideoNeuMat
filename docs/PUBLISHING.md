# GitHub Pages Notes

This folder is a self-contained GitHub Pages site for the VideoNeuMat paper page.

The page layout is adapted from the Nerfies project page template. Keep the footer attribution unless you replace the template entirely.

## Publish

1. Push this project to a GitHub repository.
2. Open the repository settings.
3. Go to **Pages**.
4. Set **Source** to **Deploy from a branch**.
5. Select the branch you use for publishing, and choose `/docs` as the folder.

## Files

- `index.html`: the project page.
- `assets/neumat_overview.mp4`: 1080p web version of `NeuMat_SIG26.mp4`, trimmed to the current homepage segment.
- `assets/paper_web.pdf`: web-optimized fallback PDF. The page's Paper links currently point to the full-resolution PDF hosted as a GitHub Release asset.
- `assets/supplementary_web.pdf`: web-optimized PDF derived from `supplementary_v2/supplementary_v2.pdf`.
- `assets/original/`: web images rendered or copied from the paper's original figure sources.

The original paper PDF and original supplementary PDF are much larger. For the final public page, host the full-resolution PDFs as GitHub Releases, institutional storage, or another stable URL, then replace the corresponding links in `index.html`.

## Google Analytics

Do not reuse the Nerfies Google Analytics ID. The page already contains a GA4 block with the placeholder `G-XXXXXXXXXX`. Create a GA4 property for this project and replace both occurrences of `G-XXXXXXXXXX` in `index.html` with your own Measurement ID.
