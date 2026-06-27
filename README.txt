SUMMER QUEST BOARD — PWA Setup Guide
=====================================

Your app is 4 files. Keep them together in the same folder at all times:
  • index.html       ← the app
  • manifest.json    ← tells Android it's an installable app
  • sw.js            ← makes it work offline
  • icon-192.png     ← home screen icon
  • icon-512.png     ← splash screen icon

────────────────────────────────────────
STEP 1: HOST THE FILES (pick one option)
────────────────────────────────────────

OPTION A — GitHub Pages (free, recommended)
1. Go to github.com and sign up / log in
2. Click "+" → "New repository"
3. Name it anything (e.g. "summer-quests"), set to Public
4. Click "uploading an existing file" and drag all 4 files in
5. Commit / save
6. Go to Settings → Pages → Source: "Deploy from branch" → branch: main → folder: / (root)
7. Save. Wait ~60 seconds.
8. Your URL will be: https://YOURUSERNAME.github.io/REPONAME

OPTION B — Netlify (easiest, drag and drop)
1. Go to netlify.com, sign up free
2. From the dashboard, drag your entire folder onto the deploy zone
3. Netlify gives you a random URL like https://quirky-name-123.netlify.app
   (you can rename it in Site settings → Domain management)

────────────────────────────────────────
STEP 2: INSTALL ON YOUR GALAXY S23
────────────────────────────────────────
1. Open Chrome on your S23
2. Go to your hosted URL
3. Wait a few seconds for the page to fully load
4. Tap the three-dot menu (⋮) in the top right
5. Tap "Add to Home screen"
6. Tap "Add" on the confirmation prompt
7. The app icon appears on your home screen!

It will open full-screen with no browser bar, just like a real app.
Your progress (XP, completed quests) is saved on each device separately
in that device's local storage.

────────────────────────────────────────
OFFLINE
────────────────────────────────────────
After your first visit, the app works fully offline. The service worker
caches everything automatically.

────────────────────────────────────────
DESKTOP
────────────────────────────────────────
On a PC, open Chrome and visit the same URL.
You'll see an install icon (⊕) in the address bar — click it to install
as a desktop app too.
