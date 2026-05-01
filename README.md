# BuyTech4.me

Landing page for an independent tech advisory practice — helping SMBs and households cut monthly tech costs and free up time.

Static HTML/CSS/JS, no build step. Deployed via GitHub Pages with custom domain `buytech4.me`.

## Local preview
Open `index.html` directly in a browser, or:
```
python3 -m http.server 8080
```

## Deployment
- Pushes to `main` are served by GitHub Pages.
- `CNAME` pins the custom domain.
- DNS at the registrar must point `buytech4.me` to GitHub Pages (apex A records or `ALIAS`/`ANAME`, plus a `CNAME` for `www` → `lordcodyody.github.io`).
