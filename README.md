# Powell Projects — AI Operations Website

## Repo summary (<=150 words)
This repository contains a complete, client-ready marketing site for an AI Operations consulting business. It is built with plain HTML, CSS, and JavaScript so it deploys cleanly to GitHub Pages with no build tools. The site includes service descriptions, process overview, pricing ranges, case-study style examples, FAQs, an about page, contact and booking flow, and basic legal pages. It also ships with a lightweight Boise skyline SVG hero background, a simple roofline chart logo, SEO metadata, sitemap.xml, robots.txt, and a favicon. The structure is designed for easy maintenance: update copy in each HTML file, adjust styles in a single stylesheet, and use placeholders for contact information and form endpoints.

## Site structure
```
/
  index.html
  how-it-works.html
  services.html
  pricing.html
  case-studies.html
  faq.html
  about.html
  contact.html
  privacy.html
  terms.html
  assets/
    css/styles.css
    js/main.js
    img/boise-skyline.svg
    img/logo-roofline.svg
    img/favicon.svg
  sitemap.xml
  robots.txt
```

## Editing content
1. Open the page you want to update (for example, `services.html`).
2. Edit headlines, paragraphs, and bullet lists directly in the HTML.
3. Keep the existing structure so spacing and layout stay consistent.
4. Update global contact info in the footer of each page.

## Swapping placeholders
Replace the following placeholders across the site:
- `[Mckayrpowell33@gmail.com]` → your email
- `[(986) 888-4844]` → your phone number
- `[BOOKING LINK]` → your calendar booking link
- `[FORM ENDPOINT]` → your Formspree endpoint (or use a mailto action instead)
- `[Month Day, Year]` → the last updated date on legal pages

## Deploy to GitHub Pages (step-by-step)
1. Push this repository to GitHub.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the **main** branch and the **/ (root)** folder.
5. Click **Save** and wait for the Pages URL to appear.
6. Update `sitemap.xml` and `robots.txt` with your live domain.

## Connect a custom domain (high level)
1. Purchase a domain from your registrar.
2. In **Settings → Pages**, add your custom domain.
3. Create DNS records at your registrar (A/AAAA or CNAME) as GitHub Pages instructs.
4. Confirm the domain and wait for DNS propagation.
5. Update `sitemap.xml` and OpenGraph URLs with your custom domain.

## Optional name ideas for the business
- Powell Projects (current)
- Boise AI Operations
- Ridgeline AI Ops
- Trailhead Automation Co.
- Clearline AI Systems
