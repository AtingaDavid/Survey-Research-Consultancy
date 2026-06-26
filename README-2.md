# Atinga Survey Research — Consultancy Website

Live at: **https://survey-research-consultancy.netlify.app** *(once deployed — see Part 2)*
Auto-deploys from GitHub repo `Survey-Research-Consultancy` via Netlify on every push.

---

## 📁 Repo File Structure

```
Survey-Research-Consultancy/
├── index.html            ← Main consultancy page
├── netlify.toml          ← Netlify config (cache rules, clean URLs)
├── README.md             ← This file
├── assets/
│   ├── css/              ← Future stylesheets
│   ├── js/               ← Future scripts
│   ├── images/           ← Logo, project photos
│   └── docs/             ← CV and PDF downloads
└── pages/                ← Future additional HTML pages
```

> **To start:** Upload `index.html`, `netlify.toml`, and `README.md` to the repo root. Add folders as needed when you have files to put in them.

---

## ✅ Pre-Launch Checklist

### 🔴 Must Do Before Launch

- [ ] Create the `Survey-Research-Consultancy` repo on GitHub (see Part 1 below)
- [ ] Upload `index.html`, `netlify.toml`, and `README.md` to repo root (see Part 1)
- [ ] Deploy on Netlify and set site name to `survey-research-consultancy` (see Part 2)
- [ ] Verify Formspree form `mbdwkyry` is active at formspree.io (see Part 3)

### 🟡 Review & Confirm in index.html

- [ ] Hero stats — years of experience, surveys completed, interviews count are current
- [ ] Project highlights (JICA Rice Green Revolution Survey, 108 villages) match your latest CV
- [ ] Services section — confirm all listed offerings are accurate
- [ ] Contact form points to correct Formspree endpoint (`mbdwkyry`)
- [ ] OG URL meta tag — update to `https://survey-research-consultancy.netlify.app`

---

## 💻 PART 1 — Create Repo & Upload Files (Windows PC)

### Files you need ready on your PC before starting:
| Filename | What it is |
|---|---|
| `index.html` | Main consultancy page (rename from `survey-consultancy_v011.html`) |
| `netlify.toml` | Netlify config (download from outputs) |
| `README.md` | This file |

### Steps:

#### Step 1 — Create the new GitHub repo
1. Open **Chrome or Edge** → go to **github.com** → sign in
2. Click the **"+"** icon (top right) → click **"New repository"**
3. **Repository name** → type exactly: **`Survey-Research-Consultancy`**
4. Set visibility to **Public**
5. Leave everything else as default → click **"Create repository"** ✅

#### Step 2 — Rename and upload your files
6. On your PC, rename `survey-consultancy_v011.html` → **`index.html`** before uploading
7. You land inside your new empty repo — click **"uploading an existing file"** or **"Add file" → "Upload files"**
8. Open **File Explorer** → navigate to your files
9. Select all 3 files (`index.html`, `netlify.toml`, `README.md`) → drag them into the GitHub upload area
10. Scroll down → leave the commit message as is → click **"Commit changes"** ✅
11. All 3 files now appear in your repo

#### Step 3 — Add asset folders (when you have files to put in them)
To create a folder on GitHub:
1. Click **"Add file" → "Create new file"**
2. In the filename box type e.g. `assets/images/.gitkeep` — this creates the folder
3. Click **"Commit changes"** ✅
4. Repeat for `assets/css/`, `assets/js/`, `assets/docs/`, and `pages/`

> Once you have actual files (images, PDFs, CSS), just drag them into the correct folder via **"Add file" → "Upload files"** and navigate into the folder first.

---

## 🌐 PART 2 — Deploy on Netlify (Windows PC, step by step)

### Step 1 — Log in to Netlify
1. Open a new tab → go to **netlify.com**
2. Click **"Log in"** (top right) → click **"Log in with GitHub"**
   > Already logged in? Skip straight to Step 2.

### Step 2 — Import your GitHub repo
3. On your Netlify dashboard click **"Add new site"**
4. Click **"Import an existing project"**
5. Click **"GitHub"** as your Git provider
   > First time? A popup asks you to authorise — click **"Authorise Netlify"** then return to this tab
6. Type `Survey-Research-Consultancy` in the search box → click it when it appears

### Step 3 — Deploy the site
7. A page titled **"Configure site and deploy"** appears
8. **Do not change anything** — all settings are already correct
9. Scroll to the bottom → click **"Deploy Survey-Research-Consultancy"**
10. Netlify shows **"Building"** with a yellow indicator
11. Wait 30–60 seconds → green **"Published"** badge appears ✅
12. Netlify assigns a random temporary name — ignore it for now

### Step 4 — Set your site name
13. Click **"Site configuration"** in the top menu
14. Click **"Site details"**
15. Click **"Change site name"** next to the random name
16. Clear it → type exactly: **`survey-research-consultancy`**
17. Click **"Save"**
18. 🎉 Your site is now live at **https://survey-research-consultancy.netlify.app**

---

## 📬 PART 3 — Verify Contact Form (Formspree)

The inquiry form uses Formspree endpoint **`mbdwkyry`** — the same one as your portfolio site.

1. Go to **formspree.io** → log in
2. **If form `mbdwkyry` shows "Active":** nothing to do ✅ Messages go to `atingad@gmail.com`
3. **If missing or showing an error:**
   - Click **"+ New form"** → name it `Survey Consultancy Inquiry` → **"Create form"**
   - Copy the new Form ID (e.g. `xpzgkryq`)
   - Go to GitHub → `index.html` → ✏️ Edit → **Ctrl+F** → search `mbdwkyry` → replace → **Commit changes** ✅

---

## 🔄 How to Update the Site in Future (Windows PC)

### Edit text or content:
1. Go to **github.com** → open **`Survey-Research-Consultancy`**
2. Click `index.html` → click the ✏️ pencil icon
3. Make your edits → click **"Commit changes"**
4. Netlify redeploys automatically in ~30 seconds ✅

### Upload a new version of the page:
1. Save your updated file as `index.html` on your PC
2. Go to your repo → **"Add file" → "Upload files"** → drag in the file → **"Commit changes"** ✅

### Add images or PDFs:
1. Go to your repo → navigate into the correct folder (e.g. `assets/images/`)
2. Click **"Add file" → "Upload files"** → drag in your files → **"Commit changes"** ✅
3. Reference them in `index.html` using relative paths e.g. `assets/images/logo.png`

### Add a new HTML page:
1. Save your new file (e.g. `services.html`) on your PC
2. Upload it to the `pages/` folder in your repo → **"Commit changes"** ✅
3. Link to it from `index.html` as `pages/services.html`

---

## 📝 Version History

| Version | Filename | Notes |
|---|---|---|
| v10 | `survey-consultancy_v010.html` | Previous version |
| **v11** | `survey-consultancy_v011.html` → deploy as `index.html` | **Current — deploy this** |
