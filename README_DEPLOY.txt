FAIL SIAP DEPLOY GITHUB PAGES

Kandungan folder ini:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png
- .nojekyll

Cara upload ke GitHub:
1. Buka repo GitHub anda.
2. Upload SEMUA fail dan folder dalam pakej ini ke root repo.
3. Pastikan nama fail utama ialah index.html.
4. Pergi ke Settings > Pages.
5. Source: Deploy from a branch.
6. Branch: main (atau branch anda), folder: /root.
7. Save.
8. Tunggu GitHub Pages siap, kemudian refresh laman.

Nota:
- Jangan upload index.html sahaja. Manifest, service worker dan folder icons mesti ada sekali.
- Untuk dapat versi terbaru selepas kemas kini, buat hard refresh sekali atau tutup-buka semula tab.
