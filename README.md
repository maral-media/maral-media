# Maral Media

Static resume site for Maral Dalaei, hosted on [GitHub Pages](https://pages.github.com/).

## Live URL (root, no path)

After setup, the site is served at:

**https://maral-media.github.io/**

GitHub only serves an organization site at the **root** when the repository is named exactly **`maral-media.github.io`**. If the repo stays named `maral-media`, the URL would be `https://maral-media.github.io/maral-media/` instead.

## One-time setup

1. **Use the correct repository name for a root URL**
   - Organization: [maral-media](https://github.com/maral-media)
   - Rename this repository to **`maral-media.github.io`**
   - On GitHub: **Settings** → **General** → **Repository name** → `maral-media.github.io`

2. **Push the site files**
   ```bash
   git add .
   git commit -m "Add Maral resume site for GitHub Pages"
   git push origin master
   ```

3. **Enable GitHub Pages**
   - Open https://github.com/maral-media/maral-media.github.io
   - Go to **Settings** → **Pages**
   - **Source:** Deploy from a branch
   - **Branch:** `master`, folder **`/ (root)`**
   - Click **Save**

4. **Wait 1–2 minutes**, then open **https://maral-media.github.io/**

Files are published from the repository **root** (`index.html`, `styles.css`) — no subfolder or build step.

## Updating the site

Edit `index.html` and/or `styles.css`, commit, and push to `master`. Changes usually appear within a minute or two.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Resume content |
| `styles.css` | Page styling |

## Notes

- Plain HTML/CSS — no build step required.
- Remote for this repo: https://github.com/maral-media/maral-media (rename to `maral-media.github.io` for root hosting).
- Custom domain: **Settings** → **Pages** → **Custom domain**.
