# Palash Solar Calculator — GitHub Pages Site

## Files
- `index.html` → Home page (palash.webflow.io)
- `solar-demo.html` → Demo/Calculator page (palash.webflow.io/solar-demo)

## How to Host on GitHub Pages (Free)

### Step 1: Create a GitHub repository
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **"New"** to create a new repository
3. Name it anything, e.g. `solar-site`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2: Upload your files
1. In your new repo, click **"Add file" → "Upload files"**
2. Upload: `index.html`, `solar-demo.html`
3. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. Go to your repo **Settings → Pages** (left sidebar)
2. Under **Source**, select **"Deploy from a branch"**
3. Select branch: **main**, folder: **/ (root)**
4. Click **Save**

### Step 4: Your site goes live
GitHub will give you a URL like:
`https://yourusername.github.io/solar-site/`

- Home page: `https://yourusername.github.io/solar-site/`
- Demo page: `https://yourusername.github.io/solar-site/solar-demo.html`

> **Note:** It may take 1–2 minutes for the site to go live after enabling Pages.

## What's Reused from Webflow
- CSS: Loaded from `cdn.prod.website-files.com` (your Webflow CDN — works as long as your Webflow site is published)
- Images: Same Webflow CDN URLs
- Fonts: Google Fonts (Playfair Display)
- JS: Webflow JS + jQuery (loaded from CDN)

## Custom Domain (Optional)
If you want a custom domain (e.g. `palashrajput.com`), go to **Settings → Pages → Custom domain** and add your domain there.
