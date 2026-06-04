# Sandeep Malik — Portfolio

Single-page portfolio site (pure HTML/CSS/JS, no build step). Live data sourced from LinkedIn and GitHub.

## Deploy to GitHub Pages (your own domain at samsandeepmalik.github.io)

1. Create a new **public** repo named exactly `samsandeepmalik.github.io` at https://github.com/new
2. Push this folder:
   ```bash
   cd "Professional Profile Management"
   git init
   git add index.html README.md
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/samsandeepmalik/samsandeepmalik.github.io.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `/ (root)` → Save.
4. Wait ~1 minute. Site is live at **https://samsandeepmalik.github.io**

## Custom domain (optional)

1. Buy a domain (e.g., sandeepmalik.dev).
2. Add a `CNAME` file containing the domain to the repo root.
3. At your DNS provider, add a CNAME record pointing `www` → `samsandeepmalik.github.io`, and A records for apex: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
4. In repo **Settings → Pages**, set the custom domain and enable *Enforce HTTPS*.

## Updating content

Everything lives in `index.html` — sections are marked with comments (`About`, `Work`, `Experience`, `Education`, `Contact`). Edit and push; Pages redeploys automatically.
