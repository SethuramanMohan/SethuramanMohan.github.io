# Sethuraman Mohan — Portfolio

Personal portfolio website for **Sethuraman Mohan**, HR Consultant, Solution Specialist & Senior Manager (AGM) with 13+ years in HCM, SaaS, and enterprise HR technology.

🌐 **Live site:** [https://sethuraman-mohan.github.io/](https://sethuramanmohan.github.io/)

---

## Deploying to GitHub Pages

### First-time setup

1. Create a new GitHub repository named **`<your-username>.github.io`**
   - e.g. `sethuraman-mohan.github.io`
2. Clone the repo locally:
   ```bash
   git clone https://github.com/<your-username>/<your-username>.github.io
   cd <your-username>.github.io
   ```
3. Copy `index.html` (and optionally `og-preview.png`) into this folder.
4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio deploy"
   git push origin main
   ```
5. Go to **Settings → Pages** in your GitHub repo and confirm the source is set to `main` branch, `/ (root)`.
6. Your site will be live at `https://<your-username>.github.io` within a minute or two.

### Updating the site

Just edit `index.html`, commit, and push — GitHub Pages rebuilds automatically.

```bash
git add index.html
git commit -m "Update portfolio"
git push origin main
```

---

## Customising meta tags

Open `index.html` and update these lines near the top to match your actual GitHub Pages URL:

```html
<meta property="og:url" content="https://YOUR-USERNAME.github.io/" />
<meta property="og:image" content="https://YOUR-USERNAME.github.io/og-preview.png" />
<meta name="twitter:image" content="https://YOUR-USERNAME.github.io/og-preview.png" />
<link rel="canonical" href="https://YOUR-USERNAME.github.io/" />
```

### Optional: add an OG preview image

For rich link previews on LinkedIn/Twitter, place a `1200×630px` image named `og-preview.png` in the root of your repo alongside `index.html`.

---

## Tech stack

- Pure HTML + CSS + Vanilla JS — zero build step, zero dependencies
- Google Fonts (loaded via CDN)
- Fully self-contained single file — works offline after first load

---

## Custom domain (optional)

If you have a custom domain (e.g. `sethuraman.dev`):

1. Add a `CNAME` file to the repo root containing just your domain:
   ```
   sethuraman.dev
   ```
2. Point your domain's DNS to GitHub Pages following [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
