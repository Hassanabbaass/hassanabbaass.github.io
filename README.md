# Hassan Abbas — personal resume site

A single-page resume site. Plain HTML and CSS with no build step, so it runs on GitHub Pages as is.

```
index.html                  the whole site (content, styles, a little JS)
assets/hassan.jpg           profile photo
assets/Hassan-Abbas-CV.pdf  the "Download CV" file
```

## Publish on GitHub Pages

1. Create a **public** repository named exactly `<your-username>.github.io`.
2. Upload `index.html`, `README.md` and the `assets` folder to the repository root
   (on GitHub, use **Add file → Upload files** and drag them in, or push with git).
3. Open **Settings → Pages**. Under **Build and deployment**, set the source to
   **Deploy from a branch** and pick `main`, folder `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io`.

## Editing

- **Text:** every section is in `index.html`, marked with `<!-- ===== SECTION ===== -->` comments.
- **LinkedIn:** the profile URL appears twice in `index.html` (hero and contact buttons).
- **New CV:** overwrite `assets/Hassan-Abbas-CV.pdf` with the same file name.
- **Colors:** change `--accent` and `--highlight` at the top of the `<style>` block.
  The dark-theme values are just below them.
- **Print:** printing the page (Ctrl+P) gives a clean one-column version.
