# Cristal Technologies – GitHub Pages Deployment Package

This package is ready for static hosting on GitHub Pages.

## Included
- index.html
- solutions.html
- case-studies.html
- contact.html
- thanks.html
- styles.css
- assets/img/logo.jpg
- assets/img/client-outcomes.png
- .nojekyll

## Contact form
The contact form is configured to send submissions to:

samir@c-tech.me

Form endpoint:
https://formsubmit.co/samir@c-tech.me

## Important first-time activation
FormSubmit requires confirming the destination email address after the first submission.
After the site goes live:
1. Submit the form once.
2. Open the activation email sent to samir@c-tech.me.
3. Confirm the form endpoint.
4. Future submissions will then be delivered normally.

## GitHub Pages deployment
1. Create or open your GitHub repository.
2. Upload all files from this package to the repository root.
3. Go to Settings > Pages.
4. Under Build and deployment, choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
5. Save.
6. Wait for GitHub Pages to publish the site.

## Notes
- .nojekyll is included so GitHub Pages serves the static files directly.
- thanks.html is used as the form success page.
- You can later replace the form backend with Formspree, Netlify Forms, or a custom API if preferred.