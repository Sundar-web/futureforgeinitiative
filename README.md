# FutureForge Initiative website

A responsive static website starter for **FutureForge Initiative**, designed to publish on GitHub Pages at no hosting cost.

## Included pages

- `index.html` — homepage, mission, program overview, approach, get involved, contact
- `about.html` — organization mission and values
- `programs.html` — program focus areas
- `privacy.html` — starter privacy notice that must be reviewed and adapted
- `styles.css` — responsive design and visual styling
- `script.js` — mobile navigation and current year
- `assets/` — SVG logo and favicon

## Before publishing

1. In `index.html`, replace `REPLACE-WITH-YOUR-EMAIL@example.org` with the official organization email address.
2. Review all copy and remove or revise any activity that does not reflect your actual plans or programs.
3. Review `privacy.html` and adapt it to the actual website practices. The included page is only a starter, not legal advice.
4. Do not claim IRS-recognized 501(c)(3) status unless and until that status has been granted.
5. Add only photos you own or have permission to use. The current design uses CSS illustrations and no stock photos.

## Publish using GitHub Pages

1. Sign in to GitHub and create a **public** repository (for example, `futureforgeinitiative.org`).
2. Upload the files and folders in this package to the repository root. Make sure `index.html` is at the top level.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish. Test the generated `github.io` address first.
6. Under **Settings → Pages → Custom domain**, enter `futureforgeinitiative.org` and save.
7. In GoDaddy DNS management, add the DNS records GitHub Pages currently specifies for your domain. GitHub's current official guide is: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
8. Keep existing MX records and any DNS records used for email. Do not remove records unless you understand their purpose.
9. Once DNS and HTTPS are ready, enable **Enforce HTTPS** in GitHub Pages settings.

DNS updates may take time to propagate. Keep the domain registration at GoDaddy; GitHub Pages is the website host.

## Editing later

To change content, open the relevant HTML file in GitHub, click the pencil/edit control, make your changes, and commit them. To change colors, fonts, spacing, or layout, edit `styles.css`.
