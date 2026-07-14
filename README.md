# Caroline Godwin — Circus Performer · Fire Dancer · Aerialist 🔥

Hand-coded portfolio site for Caroline Godwin: Las Vegas circus performer, fire dancer,
aerialist, LED artist, and coach. Pure HTML/CSS/JS — no frameworks, no build step,
no subscriptions. Made to run free forever on GitHub Pages.

## What's inside

```
index.html          — the whole site (single page)
assets/styles.css   — fire & gold theme
assets/script.js    — ember particles, scroll reveals, lazy showreel
assets/img/         — optimized performance photos
```

## Put it live on GitHub Pages (free) — 5 minutes

1. **Create the repo.** Go to [github.com/new](https://github.com/new).
   - If you name the repo **`YOURUSERNAME.github.io`** the site will live at
     `https://YOURUSERNAME.github.io/` (cleanest option — recommended).
   - Any other name (e.g. `portfolio`) works too, at
     `https://YOURUSERNAME.github.io/portfolio/`.
   - Keep it **Public** (required for free Pages) and don't add a README.

2. **Upload the files.** On the new repo page click **"uploading an existing file"**,
   then drag in **everything inside this folder** (`index.html`, the `assets` folder,
   this README). Commit.

   *Or with git:*
   ```bash
   cd carolinegodwin-site
   git init && git add -A && git commit -m "Launch 🔥"
   git branch -M main
   git remote add origin https://github.com/YOURUSERNAME/YOURREPO.git
   git push -u origin main
   ```

3. **Turn on Pages.** In the repo: **Settings → Pages → Build and deployment** —
   Source: *Deploy from a branch* — Branch: `main` / `/ (root)` — **Save**.

4. Wait ~1 minute, refresh, and your live URL appears at the top of the Pages settings.

## Later: pointing carolinegodwin.com here

When ready to drop Webflow:
1. In **Settings → Pages → Custom domain**, enter `www.carolinegodwin.com` — GitHub
   creates a `CNAME` file in the repo.
2. At your DNS provider add: `CNAME` record `www` → `YOURUSERNAME.github.io`, and
   four `A` records for the apex `@` → `185.199.108.153`, `185.199.109.153`,
   `185.199.110.153`, `185.199.111.153`.
3. Tick **Enforce HTTPS** once the certificate is issued (minutes to an hour).

## Updating the site

- **New performance?** Add a `tl-item` block in the `PERFORMANCES` section of
  `index.html` (copy an existing one and edit the text).
- **New photos?** Drop optimized JPGs (≤1600px wide is plenty) into `assets/img/`
  and swap the filenames in `index.html`.
- **Class schedule changed?** Edit the `CLASSES` section.
- Commit the change on GitHub (the pencil icon lets you edit right in the browser) —
  the live site updates automatically in about a minute.

---
© Caroline Godwin · Made by [The Creatorie](https://thecreatorie.com)
