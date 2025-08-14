moved to lumiloop-patterns

# Lumiloop — Minimal PWA Starter

This is a tiny, static Progressive Web App you can upload to GitHub **from your phone**. 
Once published (GitHub Pages), you can open it on your iPhone → **Share → Add to Home Screen** and it will work **offline**.

## Files
- `index.html` – basic page + service worker registration
- `manifest.webmanifest` – PWA metadata and icons
- `sw.js` – caches the app shell for offline use
- `icons/` – placeholder icons (replace later)

## Publish with GitHub Pages
1. Create a repository on GitHub (e.g., `lumiloop`).
2. Upload these files at the **root** of the repo (not inside a subfolder).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose **Branch: main** and **Folder: / (root)** → **Save**.
6. Wait ~60 seconds; your site will be at `https://<username>.github.io/<repo>/`.

## iPhone install
1. Open the GitHub Pages URL in **Safari**.
2. Tap **Share** → **Add to Home Screen**.
3. Launch from the new icon (standalone, full-screen).

## Next steps (later on a computer)
- Replace this starter with your React app (Vite).
- Use Vercel/Netlify for one-click deploys from your repo.
- Keep `manifest.webmanifest`, `sw.js`, and icons (or swap them for the Vite PWA plugin).

Enjoy!
