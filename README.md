# Lean Her Way social hub

This repository contains the mobile-friendly landing page used by the QR code on
Lean Her Way business cards. Its custom URL is <https://connect.leanherway.com/>.

The print-ready QR artwork is `business-card-qr.svg`. Do not print it until the
custom domain is configured and opens successfully.

## Publish with GitHub Pages

The site is configured to deploy from the `main` branch with GitHub Actions.
GitHub Pages must use **GitHub Actions** as its build source. In the DNS
settings for `leanherway.com`, add a CNAME record for `connect` pointing to
`mahrukhraza05.github.io`. GitHub Pages may take a while to verify the DNS
change and issue an HTTPS certificate.

The repository includes a `CNAME` file for the custom domain.
