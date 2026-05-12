# Portfolio (static MVP)

Plain HTML, CSS, and JavaScript — no build step. Update email, social URLs, and your **WebNovel book page URL** (search for `https://www.webnovel.com/` in `index.html` and `projects.html`) so the “Read on WebNovel” links go straight to your novel.

## Local preview

Open `index.html` in your browser, or serve the folder with any static file server so asset paths behave like production:

```bash
# Python 3
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy

Upload the project root (the folder containing `index.html`) to any static host:

- **Netlify**: Drag-and-drop the folder in the Netlify UI, or connect a Git repository with publish directory set to the repo root and no build command.
- **Cloudflare Pages**: Connect the repo; build command empty; output directory `/` (root).
- **GitHub Pages**: Repository **Settings → Pages → Build and deployment → Deploy from a branch**, choose your branch and `/ (root)` as the folder.

## Files

| Path | Purpose |
|------|---------|
| `index.html` | Home / hero |
| `about.html` | Bio and focus |
| `projects.html` | Project cards |
| `contact.html` | Email and links |
| `css/styles.css` | Layout and theme (edit CSS variables at the top) |
| `js/main.js` | Mobile nav and footer year |
| `assets/favicon.svg` | Tab icon |
