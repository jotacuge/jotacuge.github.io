# Javier Quintana González — personal website

Static academic website (plain HTML + CSS, no build step). Ready for GitHub Pages.

## Files
- `index.html` — Home (bio, research interests, contact, refereeing)
- `research.html` — Research & Data (publications, working papers, work in progress)
- `policy.html` — Policy Work
- `cv.html` — CV (embeds `assets/cv_javier_quintana.pdf`)
- `style.css` — shared styles
- this folder — CV PDF and your photo

## Add your photo
Put your photo as `photo.jpg` in this folder, then in `index.html` replace the
placeholder `<div class="placeholder">…</div>` with:

```html
<img src="assets/photo.jpg" alt="Javier Quintana González">
```

## Publish on GitHub Pages
1. Create a new **public** repository. For a personal site at
   `https://<username>.github.io`, name it exactly `<username>.github.io`.
   (Any repo name also works; the site will then live at
   `https://<username>.github.io/<repo>/`.)
2. Upload every file in this folder to the repository root (keep the this folder folder).
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`, then **Save**.
4. Wait ~1 minute and open the URL shown on that Pages settings screen.

To use a custom domain (e.g. `www.javierquintana.net`), add it under
**Settings → Pages → Custom domain**.
