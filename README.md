# ranaTek website

Static one-page site (no build step). Files:

- `index.html` – the whole site (CSS, JS and images are inlined)
- `favicon.svg`, `404.html`, `robots.txt`
- `.nojekyll` – tells GitHub Pages to serve files as-is

## Deploy on GitHub Pages
1. Create a repo and upload everything in this folder to the root of the `main` branch.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. Site goes live at `https://<username>.github.io/<repo>/`.

## Custom domain (e.g. ranatek.com.au)
Add a file named `CNAME` containing just the domain, then set the domain in Settings → Pages and add DNS records at your registrar (GitHub's docs list the A/CNAME values).
