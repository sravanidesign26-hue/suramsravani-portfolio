# Sravani Suram — Portfolio Website

A single-page portfolio site for Sravani Suram, UI/UX Designer based in Hyderabad, India.

## What's inside
- `index.html` — the entire site (HTML, CSS, and JS in one file)
- `assets/` — profile photos used on the site
- `404.html` — custom "page not found" page
- `robots.txt` / `sitemap.xml` — basic SEO files
- `.nojekyll` — tells GitHub Pages not to run this through Jekyll

## Deploying on GitHub Pages (free)

1. Create a new **public** repository on GitHub (e.g. `sravani-portfolio`).
2. Upload all the files in this folder — keep the `assets` folder structure intact.
3. Go to **Settings → Pages**.
4. Under "Build and deployment" → Source: **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)` → **Save**.
6. After a minute or two, your site is live at:
   `https://<your-github-username>.github.io/sravani-portfolio/`

## Setting up the contact form

The form uses [Formspree](https://formspree.io) (free, no backend needed):

1. Sign up free at formspree.io with your email.
2. Create a new form — you'll get a URL like `https://formspree.io/f/abcd1234`.
3. Open `index.html`, find:
   ```html
   <form class="contact-form reveal" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
4. Replace `YOUR_FORM_ID` with your real form ID.
5. Re-upload `index.html` to GitHub.

Free tier includes 50 submissions/month.

## Updating content later
- Swap the four "View case study" links once individual Behance case studies are published.
- Update photos by replacing the files in `assets/` (keep the same filenames, or update the `src` in `index.html`).
