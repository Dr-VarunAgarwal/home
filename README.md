# varunagarwal.com

Professional landing page — root/apex domain. Static site, no build step.

Separate in tone and purpose from the personal `blog.varunagarwal.com`
("lucidité") family: this page is the CV-style professional profile
(credentials, experience, research), not the personal diary.

## Files
- `index.html` — the page
- `img/headshot.jpg` — profile photo (casual selfie, used as a placeholder — swap for a proper headshot when available)
- `CNAME` — GitHub Pages custom domain config (apex `varunagarwal.com`)
- `favicon*.png` / `favicon.ico` / `apple-touch-icon.png` — generated pulse-mark icon, matching the brand mark on `contact.varunagarwal.com`

## Content source
Pulled from `Curriculum Vitae JULY 2026.docx` (Desktop\Personal) on 2026-08-18.
Re-sync this page by hand when the CV is next updated — there's no automated link between them.

## Before publishing
- [ ] Swap `img/headshot.jpg` for a proper professional photo when available
- [ ] Double check phone/email against `contact.varunagarwal.com` — this page currently mirrors it
- [ ] Create the `home` repo under github.com/Dr-VarunAgarwal, push this directory, enable GitHub Pages (Settings → Pages → Deploy from branch → main → / root)
- [ ] Point DNS: in Cloudflare, add a CNAME record for `@` (root) to `dr-varunagarwal.github.io` with proxy status set appropriately, then set the custom domain in GitHub Pages settings and enable "Enforce HTTPS" once available
