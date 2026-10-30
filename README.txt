MY BUILDING PROJECT MANAGER — ANDROID PWA

Files:
- index.html: app
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon.svg: app icon

IMPORTANT:
A Progressive Web App must be served from an HTTPS website (or localhost) to install and work offline. Opening index.html directly from Downloads will not install it as an app.

EASIEST DEPLOYMENT:
1. Create a free account at GitHub.
2. Create a new public repository, e.g. building-project-manager.
3. Upload all four files in this ZIP to the repository's root.
4. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the published https://...github.io/... address in Chrome on your Android phone.
6. In Chrome, tap ⋮ > Install app (or Add to Home screen) and confirm.
7. Open the installed app. Add a test expense, close and reopen it to verify the saved record.

DATA:
Records are saved locally in the browser on that phone. Use Download backup regularly. Restore the JSON backup if needed. This version does not sync across phones or users.
