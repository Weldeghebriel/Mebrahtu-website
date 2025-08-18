# Mebrahtu F. Weldeghebriel — Academic Website

This is a lightweight, static academic website suitable for GitHub Pages.

## Structure
- `index.html` — main site (single page)
- `assets/` — images like `profile.jpg`, `favicon.png`, `og-image.png`
- `cv/` — your CV PDF (place `Mebrahtu_Weldeghebriel_CV.pdf` here)

## Deploy (GitHub Pages)
1. Create a repo (recommended name for personal site): `<your-username>.github.io`
2. Upload all files and commit to the `main` branch.
3. In **Settings → Pages** set Source to `Deploy from a branch`, Branch `main` (root).
4. Your site will appear at `https://<your-username>.github.io/`.

### Custom domain (optional)
- Add a `CNAME` file at repo root containing your domain, e.g. `mebrahtu.org`
- Point DNS: `www` CNAME → `<your-username>.github.io`
- For apex domain, add GitHub Pages A/AAAA records per docs, then enable HTTPS in Pages.
