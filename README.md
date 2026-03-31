# HyperCoach PWA

Your pocket hypertrophy training coach — deployable in under 10 minutes.

## Files

```
hypercoach/
├── index.html      ← The entire app
├── manifest.json   ← PWA metadata
├── sw.js           ← Service worker (offline support)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## Deploy to GitHub Pages (free, ~5 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up if you don't have one.

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `hypercoach`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. Click **uploading an existing file**
2. Drag all 4 files + the `icons` folder into the upload area
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Under Source, select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**

### Step 5 — Get your URL
After ~60 seconds, your app will be live at:
```
https://YOUR-USERNAME.github.io/hypercoach/
```

---

## Add to iPhone home screen

1. Open Safari on your iPhone (must be Safari, not Chrome)
2. Go to your GitHub Pages URL
3. Tap the **Share** button (box with arrow at bottom of screen)
4. Scroll down and tap **Add to Home Screen**
5. Name it **HyperCoach** → tap **Add**

The app will appear on your home screen with the HyperCoach icon.
It will launch full screen with no browser chrome, just like a native app.
It works completely offline after first load.

---

## Notes

- All your data is saved locally on your device via localStorage
- Data persists between sessions and app relaunches
- Clearing Safari website data will erase your training history
- The app is private — no server, no account, no data leaves your device
