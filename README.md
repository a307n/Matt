# Matthew He — Portfolio

English-language personal portfolio for Matthew He, focused on product marketing and communications.

## Website

The complete static website lives in `dist/`. No dependency installation or build step is required.

- `dist/index.html`: layout, styles, copy, and interactions
- `dist/assets/`: portfolio images, portrait, and portfolio PDF
- `.github/workflows/pages.yml`: automatic GitHub Pages deployment

## Preview locally

Run `python3 -m http.server 8000 --directory dist` and visit http://localhost:8000.

## Publish to GitHub Pages

1. Push this project to the `main` branch of the selected GitHub repository.
2. In repository Settings → Pages, select **GitHub Actions** as the source.
3. Run the **Deploy portfolio to GitHub Pages** workflow, or push a new commit to `main`.
4. The successful deployment reports the public website URL.

The workflow publishes only `dist/`. Relative asset links support both root and repository-subpath hosting. Existing Sites configuration is independent of GitHub Pages.

## Update

Edit `dist/index.html` or replace assets, then push to `main` to redeploy.

Portfolio content and creative assets belong to their respective owners. No reuse license is granted by this repository.
