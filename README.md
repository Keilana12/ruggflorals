# Rugg Florals

Website for Rugg Florals, a small florist run by Isabelle Rugg.

Live at **[ruggflorals.com](https://ruggflorals.com)**.

## How it's built
Single-page static site: one `index.html` with inline CSS, hosted on GitHub Pages.

## Adding photos
Drop photos into `images/` with the filenames listed in `images/README.txt`. The site picks them up automatically — no code changes needed.

## Deploying to GitHub Pages
1. Push to the `main` branch.
2. In the GitHub repo: **Settings → Pages** → **Source: Deploy from a branch** → pick `main` / `/ (root)` → **Save**.
3. The `CNAME` file already in this repo points the site at `ruggflorals.com`. In your domain registrar, add these DNS records for `ruggflorals.com`:
   - `A` record → `185.199.108.153`
   - `A` record → `185.199.109.153`
   - `A` record → `185.199.110.153`
   - `A` record → `185.199.111.153`
   - `CNAME` record for `www` → `<your-github-username>.github.io`
4. Back in **Settings → Pages**, check **Enforce HTTPS** once the domain is verified.

## Editing content
All the words are in `index.html`. Search for the section you want (they're clearly commented, e.g. `<!-- ========== ABOUT ========== -->`) and edit the text.
