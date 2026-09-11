# P.F.A. Sturzu Mădălin — site web

Site static (HTML/CSS/JS) pentru P.F.A. Sturzu Mădălin / Coșar Autorizat, Rovinari.

## Deschidere locală

1. Deschide folderul `sturzu-cosar`.
2. Dublu-click pe `index.html` (sau: `npx serve .` / `python3 -m http.server 8080`).
3. În browser: `http://localhost:8080` dacă folosești un server local.

## Deploy pe Vercel

1. Instalează CLI: `npm i -g vercel`
2. În acest folder: `vercel`
3. Confirmă proiectul; URL-ul live apare la final.

## Deploy pe Netlify

1. Instalează CLI: `npm i -g netlify-cli`
2. În acest folder: `netlify deploy --prod --dir .`
3. Deschide URL-ul afișat în terminal.

## Deploy pe GitHub Pages

1. Creează un repo și urcă acest folder pe branch-ul `main`.
2. Settings → Pages → Source: Deploy from branch → `main` / `/ (root)`.
3. Site-ul va fi la `https://<user>.github.io/<repo>/`.
