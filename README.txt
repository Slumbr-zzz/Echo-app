ECHO — Lecture Transcriber
=========================
Free, offline speech-to-text with smart notes. No API key, no account.


HOW TO DEPLOY (5 minutes, completely free)
==========================================

GitHub Pages hosts your app at a real HTTPS URL, which is required for:
  • PWA installation ("Add to Home Screen")
  • Microphone access on mobile
  • Service worker / offline support


STEP 1 — Create a free GitHub account
  → https://github.com/signup


STEP 2 — Create a new repository
  • Go to https://github.com/new
  • Repository name: echo-app  (or anything you want)
  • Set to Public
  • Click "Create repository"


STEP 3 — Upload the files
  • Click "uploading an existing file" on the new repo page
  • Drag ALL 5 files from this folder:
      index.html
      manifest.json
      sw.js
      icon-192.png
      icon-512.png
  • Scroll down, click "Commit changes"


STEP 4 — Enable GitHub Pages
  • Go to your repo → Settings → Pages
  • Under "Source", select: Deploy from a branch
  • Branch: main  /  Folder: / (root)
  • Click Save


STEP 5 — Open on your phone
  • Your app is live at:
    https://YOUR-USERNAME.github.io/echo-app
  • Open that URL on your phone
  • Follow the install instructions inside the app (tap ?)


That's it. ECHO is now installed as a real app on your phone.
It works fully offline after the first load.


FILES IN THIS PACKAGE
=====================
  index.html      Main app
  manifest.json   PWA metadata (name, icons, colors)
  sw.js           Service worker (enables offline use)
  icon-192.png    App icon (home screen, small)
  icon-512.png    App icon (splash screen, large)
  README.txt      This file


SUPPORT
=======
  Best browser for transcription:
    Android → Chrome
    iPhone  → Safari (must use Safari for "Add to Home Screen")
