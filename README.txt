Backgammon Determined Swiss Tournament Manager - web hosting folder (version 1.2.0)

Upload ALL of these files together to one folder on a web server that uses https://
  index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-512-maskable.png

Then open the address of that folder in Chrome or Edge:
  - The "Download a copy for offline use" button appears at the bottom of the page.
  - The "Install as an app" button (or the install icon in the address bar) appears.
  - On iPhone/iPad: open in Safari > Share > Add to Home Screen.

Publishing a new version: replace index.html and also change VERSION in sw.js (for example
'ds-swiss-v1.2.0') so installed copies pick up the update the next time they are online.

Note: installing and offline mode need https:// (or http://localhost). A file opened straight from a
computer or OneDrive works as a normal page but cannot be installed.
