# Medical Research Digest

A web-based tool for discovering, searching, and archiving medical research articles from PubMed. Works across all your devices with no backend required.

## Features

- **PubMed Search**: Search 21+ clinical specialty areas directly
- **Local Archive**: All articles stored securely in your browser
- **Portable**: No login or account needed
- **Multi-Device**: Export/import to sync across desktop, laptop, tablet
- **Offline Ready**: Works offline once loaded

## Deployment to Vercel (Step-by-Step)

### What You Need
- Your existing Vercel account (✅ you have this)
- Your existing GitHub account (✅ you have this)
- GitHub Desktop (✅ you have this)

### Step 1: Create a GitHub Repository

**Option A: Via GitHub.com (Recommended for first-time)**

1. Go to **github.com** and log in
2. Click the **+** icon (top right) → **New repository**
3. Name it: `medical-research-digest`
4. Add description: "Medical research article discovery and archiving tool"
5. Choose **Public** (Vercel works best with public repos; keep it public)
6. Click **Create repository**

**Option B: Via GitHub Desktop (if you prefer)**

1. Open **GitHub Desktop**
2. File → **New Repository**
3. Name: `medical-research-digest`
4. Local path: Choose a folder on your computer
5. Click **Create**
6. Then click **Publish repository** (makes it public on GitHub.com)

---

### Step 2: Download the Project Files

1. **Download this folder** from the provided link (it contains `index.html`, `package.json`, `vercel.json`)
2. **Place all 3 files into your local repository folder**
   - If you used GitHub Desktop, it created a folder — put the files there
   - If using Option A above, clone the repo locally first (I can help with this)

---

### Step 3: Push Files to GitHub

Using **GitHub Desktop**:

1. Open GitHub Desktop
2. Select your `medical-research-digest` repository (left sidebar)
3. You should see the 3 files listed (index.html, package.json, vercel.json)
4. At the bottom, write a commit message: `Initial commit - medical research digest app`
5. Click **Commit to main**
6. Click **Publish branch** (top right)
7. Done — files are now on GitHub

---

### Step 4: Deploy to Vercel

1. Go to **vercel.com** and log in
2. Click **Add New** (top right) → **Project**
3. Click **Import Git Repository**
4. Search for `medical-research-digest` and click **Import**
5. Leave all settings as default (Vercel auto-detects it's a static site)
6. Click **Deploy**
7. **Wait 30–60 seconds** — your app is live!

You'll get a URL like: `https://medical-research-digest-abc123.vercel.app`

---

### Step 5: Bookmark & Use

1. **Bookmark the URL** in your browser (or save it)
2. **Test it**: Try searching for an article
3. **Save articles**: Click "Save to Archive"
4. **Access from any device**: The URL works on desktop, laptop, phone, any browser

---

## Using the App

### Search
- Enter keywords OR select topics from your clinical interests
- Adjust "Results Per Search" if you want more/fewer articles
- Hit "Search PubMed" — results appear instantly

### Archive
- All saved articles appear in the "Archive" tab
- Search by title, author, or journal
- Articles persist forever (stored in your browser)

### Export/Import (Multi-Device Sync)
- **On Device 1**: Settings → Export Archive (saves a JSON file)
- **On Device 2**: Settings → Import Archive (upload the JSON)
- Your archive syncs across devices instantly

---

## Troubleshooting

**Issue: Search returns no results**
- Try broader keywords (e.g., "hypertension" instead of very specific term)
- Check internet connection (needs connection to PubMed)

**Issue: Archive disappeared after clearing browser cache**
- Browser cache clear also clears local storage
- Always export your archive regularly as backup

**Issue: Vercel URL not working**
- Give it 2–3 minutes after deployment
- Refresh browser (Ctrl+F5 or Cmd+Shift+R)
- Check that you clicked "Deploy" (not just "Import")

---

## Future Enhancements

We can later add:
- Google Scholar integration
- Cloud sync to Firestore (auto-backup across devices)
- Custom topic categories
- Reading list sharing with colleagues

---

## Questions?

If you run into issues, I can help troubleshoot. The key thing: once it's on Vercel, you never touch the command line again. Just bookmark the URL and use it from anywhere.
