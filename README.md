# B.W.PROJECT — Photography Blog

Static export of the photography blog. Deployed on GitHub Pages.

## Deploy

1. Create a repo named `photography-blog` (public) on GitHub.
2. Push this folder: the `index.html` at the repo root.
3. Repo Settings → Pages → Source: "Deploy from a branch", Branch: `main` (root).
4. Live at `https://<username>.github.io/photography-blog/`.
5. Optional: add a custom domain in Settings → Pages (then add a `CNAME` file with the domain here).

## Updating

The blog is edited through Muse (artifact `photography-blog`); this folder is
re-exported and pushed after each change.
