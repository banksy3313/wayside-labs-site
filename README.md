# Wayside Labs site

Public waitlist and app pages for [waysidelabs.co.uk](https://waysidelabs.co.uk).

- Thumblog (formerly OneHand): `/thumblog/` (waitlist form; switches on only over HTTPS with a configured `data-endpoint`). `/onehand/` and `/onehand/privacy.html` are noindex redirects to it.
- Nourish Weekly: `/nourish-weekly/` is the download page. The Android app is on Google Play; the same waitlist form stays on the page for iPhone. `/nourish-weekly/free-meal-plan/` still has the launch waitlist form. The form switches on only over HTTPS with its own Make `data-endpoint` (not the Thumblog webhook). A successful sign-up reveals the free meal-plan PDF. `/nourish-weekly/free-meal-plan.pdf` stays available as a short note that points at the waitlist, so older links still open.
- Custom domain: waysidelabs.co.uk via GitHub Pages. DNS must point the apex domain at GitHub Pages (see team `HOSTING.md`).

Built by WAYDEV.
