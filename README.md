# Maral Media

A simple static website about Maral, set up for [GitHub Pages](https://pages.github.com/) free hosting.

## What you get

After you enable GitHub Pages (see below), the site will be live at:

**https://test-maral-site.github.io/maral-media/**

That URL comes from the GitHub organization/user name (`test-maral-site`) plus the repository name (`maral-media`).

## How to publish the site

1. **Push this repo to GitHub** (if you have not already):
   ```bash
   git add .
   git commit -m "Add GitHub Pages site for Maral"
   git push origin master
   ```

2. **Turn on GitHub Pages** in the repository on GitHub:
   - Open https://github.com/test-maral-site/maral-media
   - Go to **Settings** → **Pages**
   - Under **Build and deployment** → **Source**, choose **Deploy from a branch**
   - Under **Branch**, select `master` and folder **`/ (root)`**, then click **Save**

3. **Wait a minute or two** for GitHub to build and deploy. Refresh the **Pages** settings page; you should see a message like “Your site is live at …” with the URL above.

4. **Open the site** in your browser:
   ```
   https://test-maral-site.github.io/maral-media/
   ```

You should see a short page about Maral and an embedded YouTube video as a test.

## Updating the site

Edit `index.html` (and `styles.css` if you want to change styling), commit, and push to the same branch you use for Pages. Changes usually appear within a minute or two.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main page content and YouTube embed |
| `styles.css` | Basic styling |

## Notes

- This repo uses plain HTML/CSS, so no build step is required.
- If you ever rename the repo, the URL path will change to match the new repo name.
- To use a custom domain later, add it under **Settings** → **Pages** → **Custom domain**.
