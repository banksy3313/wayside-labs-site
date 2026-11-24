# Wayside Labs site

Public waitlist and app pages for [waysidelabs.co.uk](https://waysidelabs.co.uk).

- Thumblog (formerly OneHand): `/thumblog/` (waitlist form; switches on only over HTTPS with a configured `data-endpoint`). `/onehand/` and `/onehand/privacy.html` are noindex redirects to it.
- Nourish Weekly: `/nourish-weekly/` is the download page, with App Store and Google Play badges. `/nourish-weekly/free-meal-plan/` still takes an email and, after a successful sign-up, reveals the free meal-plan PDF. The form switches on only over HTTPS with its own Make `data-endpoint` (not the Thumblog webhook). The hashed PDF path is not linked in the page. `/nourish-weekly/free-meal-plan.pdf` stays as an unlinked stub so older addresses still open.
- Custom domain: waysidelabs.co.uk via GitHub Pages. DNS must point the apex domain at GitHub Pages (see team `HOSTING.md`).

Built by WAYDEV.
