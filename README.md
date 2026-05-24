# docs/ — GitHub Pages site for Forwarded Cleaner

This folder is served as the project's public website via GitHub Pages.
It exists so the Play Store listing has a real, hostable Privacy Policy URL.

## Files

- `index.html` — minimal landing page.
- `privacy-policy.html` — Play Store-ready privacy policy.

## Enabling GitHub Pages (one-time)

1. Push the project to a **public** GitHub repository (e.g.
   `github.com/<your-username>/CleanYourPhone`). Private repos cannot
   serve Pages on the free plan.
2. Go to **Settings → Pages** in that repository.
3. Under **Source**, pick:
   - Branch: `main`
   - Folder: `/docs`
4. Click **Save**. After ~1 minute the policy will be live at:
   `https://<your-username>.github.io/CleanYourPhone/privacy-policy.html`
5. Paste that URL into:
   - Play Console → Policy → App content → Privacy policy
   - AdMob → App settings → Privacy policy URL (optional but recommended)

## Updating the policy

Edit `privacy-policy.html`, bump the "Last updated" date at the top,
commit & push. Pages republishes within a minute.
