# b-tamas.github.io

Static landing page for a software architect. No build tooling or dependencies: `index.html` (embedded CSS) at the repository root, plus assets in `assets/`.

## Hero image

The page loads `assets/lighthouse.jpg` as the hero background. Add the lighthouse photo at that path. Until it exists, `assets/lighthouse-placeholder.svg` is shown instead.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publishing with GitHub Pages

The repository name `b-tamas.github.io` makes it the user site, served at <https://b-tamas.github.io>.

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.

`.nojekyll` disables Jekyll processing.
