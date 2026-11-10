# LiftLog iPhone Workout Tracker

## What's included
- Mobile-first workout tracker for your existing Monday–Friday plan
- 8-week weight/reps logging
- Copy-last-week shortcut
- Completion checkboxes and progress view
- Local browser storage and JSON backup export
- PWA manifest and service worker for Home Screen installation

## Put it online (required for a proper iPhone Home Screen app)
This is a static website. The easiest free option is GitHub Pages:
1. Create/sign in to GitHub and make a new public repository (for example `liftlog`).
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In repository Settings → Pages, select deploy from the `main` branch and `/ (root)`.
4. Wait for GitHub to publish the site. Open the published HTTPS URL in Safari on your iPhone.
5. Tap Share → Add to Home Screen → Add.

You can also host these three files on Netlify, Cloudflare Pages, or another static HTTPS host.

## Important
Workout entries are saved in the browser on the device you use. They are not automatically synced between devices. Use **Plan → Export my workout data** to create a backup. Avoid clearing Safari website data unless you have exported a backup.
