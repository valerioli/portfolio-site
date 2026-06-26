# Valerio Li — portfolio site


A single-page, editorial-style showcase of vibe-coded projects. Static HTML, no build step.

```
portfolio/
├─ index.html     ← the whole site
├─ vercel.json    ← minimal Vercel config (clean URLs)
└─ README.md      ← this file
```

---

## Deploy via GitHub → Vercel (no terminal needed)

You already have the empty Vercel project **project-lge5e**. These steps put this code into GitHub and connect it to that project, so every change you push redeploys automatically.

### 1. Create a GitHub repo (web UI)
1. Go to **https://github.com/new**.
2. Name it e.g. `valerioli-site`, keep it **Public** (or Private — both work), and click **Create repository**.

### 2. Upload these files
1. On the new repo page, click **uploading an existing file** (the link in "Quick setup").
2. Drag in **`index.html`**, **`vercel.json`**, and **`README.md`** (drag the *files*, so they sit at the repo root — not the folder).
3. Click **Commit changes**.

### 3. Connect the repo to project-lge5e
1. Open **https://vercel.com/valerioliynap-9144s-projects/project-lge5e**.
2. Go to **Settings → Git** and click **Connect Git Repository**.
3. Authorize GitHub if asked, then pick **valerioli-site**.
4. Framework preset: **Other**. Leave build command and output directory empty (it's plain static).
5. Save — Vercel deploys automatically. You'll get a live URL in ~30 seconds.

> If Vercel won't let you attach a repo to the existing empty project, just use **Add New → Project → Import** `valerioli-site` instead. It creates a project from the repo, which is just as good — you can ignore or delete the empty `project-lge5e`.

### 4. Claim your free address
1. In the project → **Settings → Domains**.
2. Add **`valerioli.vercel.app`** (or `valerio-li`, `valerio-builds`, etc. if taken) and **Set as Primary**.

Live at `valerioli.vercel.app`. 🎉

---

## Updating later
Edit `index.html` in GitHub (pencil icon → commit) and Vercel redeploys on its own.

When project #2 ships, find the `02` card in `index.html` and:
- change the title, description, and tags,
- change `class="work soon"` to `class="work live"`,
- wrap it in a link or set the `href` to the new project URL.

## Quick edits before launch
- Replace the placeholder contact email: search `hello@example.com` in `index.html`.
- Add social links in the footer if you want (GitHub, X, etc.).
