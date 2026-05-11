# Binson SR · Portfolio

Cinematic real estate videography portfolio for Binson SR — Dubai.

---

## 📦 Complete folder structure

```
binson-portfolio/
├── .gitignore                              ← Git config
├── README.md                               ← this file
├── index.html                              ← THE WEBSITE
├── assets/
│   ├── binson.png                          ← profile photo
│   ├── reel.mp4                            ← main reel (71 MB)
│   ├── work-01.mp4                         ← community video (6 MB)
│   └── work-02.mp4                         ← developer video (1.6 MB)
└── fonts/
    ├── open-sauce-sans-300.woff2           ← Open Sauce Sans Light
    ├── open-sauce-sans-400.woff2           ← Open Sauce Sans Regular
    ├── open-sauce-sans-400-italic.woff2    ← Open Sauce Sans Regular Italic
    ├── open-sauce-sans-500.woff2           ← Open Sauce Sans Medium
    ├── open-sauce-sans-600.woff2           ← Open Sauce Sans SemiBold
    ├── open-sauce-sans-700.woff2           ← Open Sauce Sans Bold
    ├── open-sauce-sans-800.woff2           ← Open Sauce Sans ExtraBold
    ├── open-sauce-sans-900.woff2           ← Open Sauce Sans Black
    ├── jetbrains-mono-300.woff2            ← JetBrains Mono Light
    ├── jetbrains-mono-400.woff2            ← JetBrains Mono Regular
    └── jetbrains-mono-500.woff2            ← JetBrains Mono Medium
```

**Total: 3 files + 11 fonts + 4 assets · ~80 MB**

Everything is self-contained — no internet connection needed for fonts. Drop the folder anywhere and `index.html` works offline.

---

## 🚀 Host on GitHub Pages — step by step

### Step 1 — Create a GitHub account
If you don't already have one:
1. Go to [github.com](https://github.com)
2. Sign up with your email (free)

### Step 2 — Create a new repository
1. Once logged in, click the **+** icon top-right → **New repository**
2. Repository name: `binson-portfolio` (becomes part of your URL)
3. Set it to **Public** (required for free GitHub Pages)
4. **Do NOT** check "Initialise with README"
5. Click **Create repository**

### Step 3 — Upload the files
1. On the empty repo page, click **uploading an existing file**
2. **Drag everything** from your `binson-portfolio` folder onto the page:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - the whole `assets/` folder
   - the whole `fonts/` folder
3. Scroll down → commit message: "Initial upload" → click **Commit changes**
4. Wait for the upload (1–3 minutes — the reel is the biggest)

> ⚠️ Upload everything in one go so it becomes a single commit.

### Step 4 — Turn on GitHub Pages
1. In your repo, click **Settings** (top of the repo)
2. Left sidebar → **Pages**
3. Under **Source**, change "None" to **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 5 — Your site is live
- Wait 1–2 minutes
- Refresh the Pages settings page
- You'll see: **Your site is live at https://YOUR-USERNAME.github.io/binson-portfolio/**
- Share that link anywhere

---

## ⚠️ Showing hidden files

The `.gitignore` file is hidden by default on Mac and Windows. Before you drag, make hidden files visible:

- **Mac:** Open the folder in Finder → press `Cmd + Shift + .` (period)
- **Windows:** Open the folder → View tab → check **Hidden items**

If you skip `.gitignore` the site still works — it just helps keep junk files like `.DS_Store` out of your repo.

---

## 🔄 How to update the site later

**To swap or add a video / photo:**
1. Go to your repo on github.com
2. Open the file you want to replace (e.g. `assets/reel.mp4`)
3. Click **Add file → Upload files** or the pencil icon
4. Upload the replacement → commit
5. Site auto-updates in 1–2 minutes

**To add a new video card on the page:**
1. Drop the video into `assets/`
2. Edit `index.html` — find a `<div class="card-3d">` block, copy it, swap the filename inside
3. Commit

---

## ✏️ Quick edits

Search inside `index.html` to change:

| What | Find |
|---|---|
| Email | `binsonsr224@gmail.com` |
| Instagram | `binson_sr` |
| Stats (100+, 20+, 4Y) | `hero-stats` |
| About bio text | `Binson SR` |

---

## 🎨 What the site does

- Pure black void with drifting dust particles
- 3D floating card gallery — cards tilt with the cursor
- Hover a card → it pulls forward, plays a muted preview
- Click → full-screen video lightbox
- Side filter panel — `ALL / COMMUNITY / AGENCY / DEVELOPER / YOUTUBE`
- "ASK ME ANYTHING" pill button jumps to contact
- Custom cursor on desktop, fully responsive on mobile
- Single cream tone throughout — all text in one colour
- Open Sauce Sans + JetBrains Mono typography (loaded locally)
- Loader counts 000 → 100 on first visit

---

## 📞 Contact (baked in)

- **Email:** binsonsr224@gmail.com
- **Instagram:** [@binson_sr](https://www.instagram.com/binson_sr/)

---

## 🛠 Tech notes

- No build step. Pure HTML/CSS/JS — works anywhere.
- All assets local, including fonts. **No external dependencies.**
- Videos are H.264 MP4 — universal browser support.
- Fonts are WOFF2 — modern, compressed, all browsers support them.

---

© 2026 — Binson SR · Dubai · UAE
