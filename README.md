# POP Application (PWA) - Starter

This is a beginner-friendly React + Vite Progressive Web App starter for the POP food app.
Structure:
- Static menu data in `src/data/menu.js`
- Login with localStorage
- Menu list, detail modal, add to cart, favorites (localStorage)
- PWA manifest + simple service worker

## Run locally
1. Install dependencies:
   ```
   npm install
   ```
2. Run dev server:
   ```
   npm run dev
   ```
3. Open `http://localhost:5173`

## Build & Deploy to GitHub Pages
1. Set `homepage` in package.json to `https://<YOUR-USERNAME>.github.io/<REPO>`
2. Install dev dependency (already listed): `npm install --save-dev gh-pages`
3. Deploy:
   ```
   npm run deploy
   ```

## Files to change (logo and meal images)
- Place your logo at `public/icons/logo-pop.png`
- Replace meal images in `public/icons/meal1.jpg` ... `meal5.jpg` or edit `src/data/menu.js` to use external URLs.

