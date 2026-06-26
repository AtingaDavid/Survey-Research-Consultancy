# Atinga Survey Research — Consultancy Website

Live at: **https://survey-research-consultancy.netlify.app** *(once deployed — see Part 2)*
Auto-deploys from GitHub repo `Survey-Research-Consultancy` via Netlify on every push.

---

## 📁 Repo File Structure

```
Survey-Research-Consultancy/
├── index.html       ← Main consultancy page (rename from survey-consultancy_v011.html)
├── netlify.toml     ← Netlify config (do not edit)
└── README.md        ← This file
```

> **Important:** When uploading to GitHub, rename `survey-consultancy_v011.html` to `index.html` so Netlify serves it as the homepage of the new site automatically.

---

## ✅ Pre-Launch Checklist

### 🔴 Must Do Before Launch

- [ ] Create the `Survey-Research-Consultancy` repo on GitHub (see Part 1 below)
- [ ] Upload files to the repo (see Part 1 below)
- [ ] Deploy on Netlify and set site name to `survey-research-consultancy` (see Part 2 below)
- [ ] Verify Formspree form `mbdwkyry` is active at formspree.io (see Part 3)

### 🟡 Review & Confirm in index.html

- [ ] Hero stats — years of experience, surveys completed, interviews count are current
- [ ] Project highlights section (JICA Rice Green Revolution Survey, 108 villages) matches your latest CV
- [ ] Services section — confirm all listed service offerings are accurate
- [ ] Contact form points to correct Formspree endpoint (`mbdwkyry`)
- [ ] OG URL tag — update from `https://davidatinga.netlify.app/survey` to `https://survey-research-consultancy.netlify.app` once the new site name is confirmed

---

## 💻 PART 1 — Create Repo & Upload Files (Windows PC)

### Files you need ready on your PC before starting:
| Filename | What it is |
|---|---|
| `index.html` | Main consultancy page (rename from `survey-consultancy_v011.html`) |
| `netlify.toml` | Netlify config |
| `README.md` | This file |

### Steps:

#### Step 1 — Create the new GitHub repo
1. Open **Chrome or Edge** → go to **github.com** → sign in
2. Click the **"+"** icon (top right) → click **"New repository"**
3. **Repository name** → type exactly: **`Survey-Research-Consultancy`**
4. Set visibility to **Public**
5. Leave everything else as default → click **"Create repository"** ✅

#### Step 2 — Upload your files
6. You land inside your new empty repo
7. Click **"uploading an existing file"** (shown in the empty repo page) — or click **"Add file" → "Upload files"**
8. A drag-and-drop area appears — open **File Explorer** on your PC
9. Rename `survey-consultancy_v011.html` → **`index.html`** before dragging
10. Select all 3 files (`index.html`, `netlify.toml`, `README.md`) → drag them into the GitHub upload area
11. Scroll down → leave the commit message as is → click **"Commit changes"** ✅
12. Wait a few seconds → all 3 files will be listed in your repo

---

## 🌐 PART 2 — Deploy on Netlify (Windows PC, step by step)

### Step 1 — Log in to Netlify
1. Open a new tab → go to **netlify.com**
2. Click **"Log in"** (top right)
3. Click **"Log in with GitHub"**
   > Already logged in? Skip straight to Step 2.

### Step 2 — Import your GitHub repo
4. Once logged in you land on your **Netlify dashboard**
5. Click the **"Add new site"** button
6. Click **"Import an existing project"**
7. Click **"GitHub"** as your Git provider
   > First time connecting GitHub to Netlify? A popup asks you to authorise — click **"Authorise Netlify"** then come back to this tab
8. A search box appears — type `Survey-Research-Consultancy` → click **`Survey-Research-Consultancy`** when it appears

### Step 3 — Deploy the site
9. A page titled **"Configure site and deploy"** appears
10. **Do not change anything on this page** — all settings are already correct
11. Scroll to the very bottom → click the **"Deploy Survey-Research-Consultancy"** button
12. Netlify shows **"Building"** with a yellow indicator
13. Wait about 30–60 seconds → it changes to a green **"Published"** badge ✅
14. Netlify gives your site a random temporary name like `fluffy-fox-abc123.netlify.app` — ignore this for now

### Step 4 — Set your site name
15. Look at the top menu → click **"Site configuration"**
16. Click **"Site details"**
17. Click the **"Change site name"** button next to the random name
18. Clear the random name completely → type exactly: **`survey-research-consultancy`**
19. Click **"Save"**
20. 🎉 Your site is now live at **https://survey-research-consultancy.netlify.app** — open it in a new tab to confirm!

---

## 📬 PART 3 — Verify Contact Form (Formspree)

The inquiry form uses Formspree endpoint **`mbdwkyry`** — the same one as your portfolio site.

1. Open a new tab → go to **formspree.io** → click **"Log in"**
2. Once logged in, look at your list of forms
3. **If you see form `mbdwkyry` and it shows "Active":**
   → Nothing to do ✅ Inquiry messages will go to `atingad@gmail.com`
4. **If the form is missing or shows an error:**
   - Click **"+ New form"**
   - Name it `Survey Consultancy Inquiry` → click **"Create form"**
   - Copy the new Form ID shown (e.g. `xpzgkryq`)
   - Go to GitHub → `index.html` → ✏️ Edit → press **Ctrl+F** → search `mbdwkyry`
   - Replace it with your new Form ID → **Commit changes** ✅

---

## 🔄 How to Update the Site in Future (Windows PC)

### Edit text or content:
1. Go to **github.com** → open **`Survey-Research-Consultancy`**
2. Click `index.html` → click the ✏️ pencil icon
3. Make your edits → click **"Commit changes"**
4. Netlify redeploys automatically in ~30 seconds ✅

### Upload a new version of the page:
1. Save your updated file as `index.html` (exact name) on your PC
2. Go to your repo → click **"Add file" → "Upload files"**
3. Drag in the new file — GitHub will replace the existing `index.html`
4. Click **"Commit changes"** ✅

---

## 📝 Version History

| Version | Filename | Notes |
|---|---|---|
| v10 | `survey-consultancy_v010.html` | Previous version |
| **v11** | `survey-consultancy_v011.html` → deploy as `index.html` | **Current — deploy this** |
