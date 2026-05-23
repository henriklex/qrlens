# qrlens

Marketing + privacy site for [QR Lens](https://apps.apple.com/app/id6772594695) — a free, no-ads, on-device QR and barcode scanner for iPhone built for inspecting, not just opening.

## What's here
- `index.html` — marketing/landing page (linked as App Store Connect Marketing URL + Support URL)
- `privacy.html` — Privacy Policy (linked as App Store Connect Privacy Policy URL)
- `assets/screenshot.jpg` — hero image (replace with a real Detail-view screenshot when ready)
- `.nojekyll` — disables Jekyll on GitHub Pages so file paths work as-is

## Deploy to GitHub Pages

1. Create a new public GitHub repo at `henriklex/qrlens`.
2. Push this directory:
   ```
   cd /Users/opera_user/Projects/qrlens
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin git@github.com:henriklex/qrlens.git
   git push -u origin main
   ```
3. In repo Settings → Pages, set source to `main` branch, `/` (root). Save.
4. Wait ~1 min, then verify:
   - https://henriklex.github.io/qrlens/ resolves to the landing page
   - https://henriklex.github.io/qrlens/privacy.html resolves to the Privacy Policy

These are the URLs already entered in App Store Connect for QR Lens (Marketing, Support, Privacy Policy). The App Store reviewer **will** visit them — make sure they're live before clicking **Add for Review** on the iOS App 1.0 page.

## Optional: replace the screenshot
The placeholder `assets/screenshot.jpg` should be replaced with an actual QR Lens Detail-view screenshot at 240×~500px (rendered at 6px border + 28px radius). Easiest source: capture from the iPhone 16 Pro Max simulator after running the app, then crop.
