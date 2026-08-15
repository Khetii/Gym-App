Hunter Training System PWA

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

To install on Android, the folder must be hosted over HTTPS (or localhost).
Easy options:
1. Netlify Drop: drag this whole folder into Netlify Drop.
2. GitHub Pages: upload these files to a repo and enable Pages.
3. Any HTTPS web host.

Then open the URL in Chrome and choose Install app / Add to Home screen.

Note:
Data is stored in localStorage for the hosted origin. Data from the earlier local HTML file
does not automatically transfer into the PWA.
