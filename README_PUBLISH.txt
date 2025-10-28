# Ebony Site — Publish Ready

## Replace Images
Put your real images in `assets/` and keep the same filenames to auto‑swap:

- `assets/hero.svg` → homepage hero
- `assets/headshot.svg` → headshot in Contact/Press
- `assets/thumb_dropoff.svg` → “The Drop-Off” card
- `assets/thumb_advice.svg` → Advice Media card
- `assets/thumb_campaign.svg` → Campaign Analysis card
- `assets/thumb_blog1.svg` → Blog post 1
- `assets/thumb_blog2.svg` → Blog post 2
- `assets/thumb_blog3.svg` → Blog post 3

You can replace `.svg` with `.jpg`/`.png` — just keep the names and update the links if the extension changes.

## Working Contact Form
**Formspree (fastest):**
1. Create a form at https://formspree.io/forms
2. Copy the form ID (looks like `xayzpqwe`).
3. In `ebony_site_publish_ready.html`, replace `YOUR_FORMSPREE_ID` in the form `action` URL.

**Netlify (no backend needed, Netlify hosting only):**
- Keep `data-netlify="true"` and the hidden `form-name` input.
- Deploy the site to Netlify; submissions will appear in Netlify Forms.

## Which file to upload
Use **`ebony_site_publish_ready.html`** as your homepage (or set it as index.html). Keep these in the same folder:
- `blog_index.html`, `post_*.html`
- `projects.html`, `projects.json`
- `feed.xml`
- `assets/` (folder with images)

## Résumé Links
Update the two PDF filenames (or upload your PDFs and change the links):
- `Ebony_Cuthbert_Professional_Resume.pdf`
- `Ebony_Cuthbert_Creative_Portfolio_Resume.pdf`
