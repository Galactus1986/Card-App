# CardVault

A free, mobile-first, offline-ready card collection PWA. No build tools or backend required.

## Publish on GitHub Pages
1. Create a public GitHub repository.
2. Upload **all four files** (`index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`) to the repository root.
3. Open Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Open the resulting HTTPS GitHub Pages URL on your phone. In Safari choose Share → Add to Home Screen; on Chrome use Install app / Add to Home Screen.
5. Open once while online. Subsequent launches work offline after the service worker finishes caching.

## Storage and backups
Photos and card data live in your current browser's IndexedDB, not GitHub. Export a JSON backup regularly using Collections → Export backup. Import the backup on another device to copy your collection. Clearing site data, using private mode, or removing the PWA may delete locally stored cards. No automatic device sync is provided.

## Features
- Gallery with collection filters
- Swipe left/right between cards; tap to flip in 3D
- Image upload, name, description, rarity, holographic shine
- Create, rename, and delete collections (deleting a collection moves cards to another collection)
- Edit/delete cards, random card mode
- Offline app shell, local storage, JSON backup and restore
