
# Tarun Logistics Website (GitHub Pages)

A modern, multi‑page static website for **Tarun Logistics**, designed for GitHub Pages and a custom domain.

## Structure
- `index.html`, `about.html`, `services.html`, `gallery.html`, `contact.html`
- `assets/css/styles.css`
- `assets/js/main.js`
- `assets/img/logo.png`
- `CNAME` (contains `tarunlogistics.com`)

## Deploy on GitHub Pages
1. Create a new public repository (e.g., `tarunlogistics.com` or any name).
2. Upload all files in this folder to the repo root (keep `CNAME` at the root).
3. In **Settings → Pages**, set **Source** to `Deploy from a branch`, Branch `main`, Folder `/root`.
4. Wait for the Pages build. Your site will resolve at `https://tarunlogistics.com/` once DNS is pointed to GitHub.

## DNS (custom domain)
- Add these **A records** at your domain provider pointing to GitHub Pages IPs:
  - `@` → `185.199.108.153`
  - `@` → `185.199.109.153`
  - `@` → `185.199.110.153`
  - `@` → `185.199.111.153`
- (Optional) `www` CNAME → `your-username.github.io` if you want `www.tarunlogistics.com` to work.
- Keep the `CNAME` file in the repo with `tarunlogistics.com` inside.

## Editing
- Replace placeholder contact info and address in `contact.html`.
- You can swap Unsplash image URLs with your own photos or other Unsplash images.
- Styling is in `assets/css/styles.css`.
