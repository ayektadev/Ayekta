# Ayekta Waitlist — GitHub Pages Setup

## 1) Create the repo
- On GitHub, click **New repository** → name it `ayekta` or `ayekta-landing`.
- Add a `README.md` (optional).

## 2) Upload files
- Upload `index.html` and the `assets/` folder (contains `logo.svg`).

## 3) Enable GitHub Pages
- Go to **Settings → Pages**.
- Under **Build and deployment**, set **Source** to **Deploy from a branch**.
- Select branch **main**, folder **/** (root). Save.
- Your site will publish to `https://<your-username>.github.io/<repo-name>/`.

## 4) Connect the waitlist form
- In `index.html`, replace the form `action` URL (`https://formspree.io/f/your-endpoint`) with your actual endpoint (Formspree/Basin/Getform), or embed a Google Form.
- There’s a simple honeypot. For heavy traffic, add hCaptcha/Turnstile.

## 5) Optional: Custom domain
- Buy `ayekta.org` (later). In **Settings → Pages**, set **Custom domain** and add DNS `CNAME` to `<your-username>.github.io`.
- Force HTTPS once the certificate is ready.

## 6) Optional: Analytics
- Add Plausible/Umami script to `index.html` for privacy‑friendly stats.

## Notes
- This is static HTML — no backend needed.
- Keep copies minimal and grounded to avoid “vaporware” vibes.
