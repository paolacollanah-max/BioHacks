# Biohacks — Static Site

A static, framework-free website for Biohacks. Pure HTML/CSS/JS — no build step.

## Pages
- `index.html` — Home (background video hero)
- `about.html` — About
- `science.html` — The Science
- `styles.css` — Shared styles
- `assets/` — Video, poster image, brand image

## Run locally
Just open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages
1. Create a new GitHub repository and push these files to the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source = Deploy from a branch**, **Branch = main**, **Folder = / (root)**, then **Save**.
4. Your site goes live at `https://<user>.github.io/<repo>/` in a minute or two.

### Custom domain (optional)
- In **Settings → Pages → Custom domain**, enter your domain and save.
- At your domain registrar, add a CNAME record pointing to `<user>.github.io` (or A records to GitHub's IPs for an apex domain).

## Fonts
Cormorant Garamond + Jost are loaded from Google Fonts (requires an internet connection).
