# Darsh Patel — Portfolio

A clean, professional portfolio site built for GitHub Pages, migrated from Google Sites.

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it exactly: `darsh1406.github.io`  
   _(replace `darsh1406` with your GitHub username if different)_
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload your files

**Option A — via GitHub website (easiest):**
1. Open your new repo
2. Click **Add file → Upload files**
3. Drag and drop `index.html` into the window
4. Scroll down and click **Commit changes**

**Option B — via Git (if you have Git installed):**
```bash
git clone https://github.com/darsh1406/darsh1406.github.io
cd darsh1406.github.io
# Copy index.html into this folder
git add .
git commit -m "Add portfolio"
git push
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Visit your site

After ~1 minute, your portfolio will be live at:
```
https://darsh1406.github.io
```

---

## 📁 File Structure

```
darsh1406.github.io/
└── index.html       ← your entire portfolio (single page)
```

## 🖼️ About Images

Images are loaded directly from your Google Sites CDN — no re-uploading needed. 
If you ever take down your Google Site, the images may stop loading. In that case,
download them from Google Sites and place them in an `assets/images/` folder, 
then update the `src` paths in `index.html`.

## ✏️ How to Update Content

Open `index.html` in any text editor and search for the section you want to edit.
Each project and research item is clearly commented and follows the same structure.
