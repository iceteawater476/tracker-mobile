# Finals Tracker — Mobile App

A Progressive Web App (PWA) you can install on your phone.
All data is saved locally on your device. Works offline.

---

## How to Install on Your Phone

### Option A — Android (Chrome) [Recommended]
1. Open Chrome on your phone
2. Go to the URL where you're hosting these files (see Hosting below)
3. Tap the three-dot menu (⋮) → "Add to Home Screen" → "Install"
4. The app appears on your home screen like a native app

### Option B — iPhone (Safari)
1. Open Safari on your iPhone
2. Go to the URL where you're hosting these files
3. Tap the Share button (□↑) → "Add to Home Screen" → "Add"
4. The app appears on your home screen

---

## How to Host (pick one)

### Easiest: Python local server (same WiFi)
1. Open Terminal / Command Prompt
2. Navigate to this folder:
   cd path/to/finals-app
3. Run:
   python3 -m http.server 8080
4. On your phone (same WiFi), open:
   http://YOUR_COMPUTER_IP:8080
   (Find your IP: run `ipconfig` on Windows or `ifconfig` on Mac/Linux)

### Free online hosting: GitHub Pages
1. Create a free GitHub account at github.com
2. Create a new repository
3. Upload all files in this folder to the repo
4. Go to Settings → Pages → Source: main branch
5. Your app will be live at: https://yourusername.github.io/repo-name

### Free online hosting: Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag and drop this entire folder onto the page
3. You get a live URL instantly — open it on your phone!

---

## Files in this folder
- index.html   — The main app
- manifest.json — Makes it installable as an app
- sw.js         — Service worker (offline support)
- icon-192.svg  — App icon (small)
- icon-512.svg  — App icon (large)

---

## Using on PC (no install needed)
Just open index.html in any browser. Data saves automatically.
