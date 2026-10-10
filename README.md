# Everyday Helper Upgrade

Files to upload to your existing GitHub Pages repository:
- `index.html`: upgraded app
- `manifest.json`: installable-app settings
- `sw.js`: basic offline app-shell caching
- `icon-192.png` and `icon-512.png`: app icons
- `MONETIZATION-ROADMAP.md`: realistic monetisation plan

## Upload steps
1. Keep a backup copy of your current `index.html`.
2. Open https://github.com/omoshoderu001-afk/everyday-helper
3. Click **Add file → Upload files**.
4. Upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png`.
5. Confirm replacing `index.html` if GitHub asks, then click **Commit changes**.
6. Wait a few minutes and visit https://omoshoderu001-afk.github.io/everyday-helper/ . If the old version appears, press `Ctrl+F5` or try a private window.

The app keeps the existing `everydayHelperData_v1` localStorage key and supports the older budget data shape. Still, make a backup first.

## Install on phone
- Android Chrome: open the site menu and choose **Install app** or **Add to Home screen**.
- iPhone/iPad: open in Safari, tap Share, then **Add to Home Screen**.
- Desktop Chrome: use the install icon in the address bar or the app's **Install app** button when offered.

Offline caching works after the first successful visit. User data stays in that browser. Use **Back up** to export a JSON copy before clearing browser data or changing devices.
