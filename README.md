# TapDeck – Privacy Policy

Bilingual (Japanese / English) static privacy policy page for **TapDeck**.

## How to publish on GitHub Pages (free, no credit card)

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create an account).
2. Click **New repository**.
3. Name it `tapdeck-privacy` (or any name you like — the URL will reflect this).
4. Set it to **Public** (required for the free GitHub Pages tier).
5. Click **Create repository**.

### Step 2 — Push this folder

In PowerShell, from inside `privacypolicy/`:

```powershell
cd C:\Users\junkr\flutter_workspace\privacypolicy
git init
git add .
git commit -m "Initial privacy policy"
git remote add origin https://github.com/YOUR_USERNAME/tapdeck-privacy.git
git branch -M main
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under **Source**, select `Deploy from a branch`.
3. Choose **main** branch, `/ (root)` folder.
4. Click **Save**.

After about 1–2 minutes, your page will be live at:

```
https://YOUR_USERNAME.github.io/tapdeck-privacy/
```

### Step 4 — Add the URL to your app store listing

Paste the GitHub Pages URL into the **Privacy Policy URL** field in Microsoft Partner Center when submitting to the Microsoft Store.

---

## Other free hosting options

| Service | Notes |
|---|---|
| **GitHub Pages** ⭐ | Free, no limit, custom domain supported |
| **Netlify** | Drag-and-drop deploy, free tier, custom domain |
| **Cloudflare Pages** | Fastest CDN, free, custom domain |
| **Vercel** | Also free, but geared toward app frameworks |

For a single static HTML file, **GitHub Pages is the simplest and most permanent option**.

---

## Customization checklist

- [ ] Replace `junkmecha` with your actual GitHub username or display name throughout `index.html`
- [ ] Update the `Last updated` date when you change the policy
- [ ] Add your GitHub repository or contact URL if you have one
- [ ] Optionally add a custom domain (Settings → Pages → Custom domain)
