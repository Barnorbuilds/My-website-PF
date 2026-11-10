# JJesdro Personal & Business Portfolio

A responsive, static portfolio website for Benjamin Barnor and the JJesdro brand.

## Files
- `index.html` — page content and sections
- `styles.css` — responsive executive-style design
- `script.js` — mobile navigation and current year
- `CNAME` — custom domain declaration for GitHub Pages

## Before publishing
1. Replace the email address `hello@jjesdro.com` if that is not your active email.
2. Replace the LinkedIn placeholder URL with your actual profile.
3. Add your professional photograph: replace the `.portrait-placeholder` block in `index.html` with an image element and update the CSS.
4. Review each project description and add screenshots, demo links, and your exact role/results where available.
5. Add a CV PDF and link it from the About section if desired.

## Deploy with GitHub Pages
1. Upload these files to the root of the repository you want to publish.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. In the Pages custom domain field, enter `jjesdro.com`. The included `CNAME` file also declares this domain.
5. Configure DNS at GoDaddy using GitHub's current official custom-domain instructions. Typically this involves four A records for the apex domain and a `www` CNAME pointing to `Barnorbuilds.github.io`. Verify the exact current values in GitHub's documentation before changing DNS.
6. Wait for DNS propagation, then enable **Enforce HTTPS** in GitHub Pages.

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Notes
This is a static site and does not require a database, server, build command, or paid hosting. The contact email link requires a real mailbox to be configured.
