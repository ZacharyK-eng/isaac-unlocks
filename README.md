# Isaac Unlock Profile — GitHub Pages

A static, offline-capable iPhone progression tracker. **Not yet an EXchive .dat exporter.**

## Deploy (no command line)
1. Sign in to GitHub and create a **public** repository, e.g. `isaac-unlocks`.
2. Choose **Add file → Upload files** and upload the **contents of this folder** (`index.html`, `sw.js`, `manifest.webmanifest`, and both PNG icons) to the repository root. Commit the changes.
3. Open **Settings → Pages → Build and deployment**. Set **Source: Deploy from a branch**, **Branch: main**, folder **/(root)**, then Save.
4. Visit `https://YOUR-USERNAME.github.io/isaac-unlocks/` once Pages finishes publishing.
5. On iPhone open the URL in Safari → Share → **Add to Home Screen** → Add. Open the icon while online once, then it should work offline after caching.

## Saving
Selections are automatically saved to browser storage on that device and origin. Safari and the installed Home Screen app may not share storage. Use the same entry point each time. **Save backup to Files** exports a JSON profile, and **Import JSON backup** restores it. Keep backups in Files/iCloud Drive. Clearing Safari website data or uninstalling the Home Screen app may erase local data.

## Privacy
The app has no analytics, server-side profile storage, or external dependencies. GitHub Pages serves the static app files; progress stays on the device unless you share a JSON backup. A public repository means the app code is public, not your locally stored progress.

## Limitations
Achievement IDs are numbered rather than fully named/mapped, and the editor does not produce a valid Repentance+ `.dat` save. The profile is a manual tracker pending verified mapping and binary export support.
