# UdhaarBook 📒
> Never forget a rupee — track udhaar, send WhatsApp reminders, generate invoices.

## 🚀 Deploy to Vercel (3 ways)

---

### ✅ Way 1 — Drag & Drop (Easiest, 60 seconds)

1. Go to **[vercel.com](https://vercel.com)** → Sign up / Log in (free)
2. On your dashboard, click **"Add New Project"**
3. Scroll down to **"Or deploy without a Git repository"**
4. **Drag your project folder** (the one with `index.html` + `vercel.json`) onto the upload area
5. Click **Deploy** → Done! You get a live URL like `https://udhaarbook.vercel.app`

---

### ✅ Way 2 — GitHub + Vercel (Best for updates)

**Step 1: Push to GitHub**
```bash
# Install git if not already
git init
git add .
git commit -m "initial deploy"

# Create a new repo on github.com, then:
git remote add origin https://github.com/YOUR_USERNAME/udhaarbook.git
git push -u origin main
```

**Step 2: Connect to Vercel**
1. Go to **[vercel.com](https://vercel.com)** → "Add New Project"
2. Click **"Import Git Repository"**
3. Select your `udhaarbook` repo
4. Leave all settings as default (Vercel auto-detects it's a static site)
5. Click **Deploy**

**✨ Bonus:** Now every time you push to GitHub, Vercel auto-deploys the update!

---

### ✅ Way 3 — Vercel CLI (Developer way)

```bash
# Install Vercel CLI
npm install -g vercel

# Go into your project folder
cd udhaarbook

# Deploy!
vercel

# Follow the prompts:
# ? Set up and deploy? → Y
# ? Which scope? → your account
# ? Link to existing project? → N
# ? Project name? → udhaarbook
# ? In which directory? → ./
# Done! You get a URL.

# For production deploy:
vercel --prod
```

---

## 📁 Project Structure

```
udhaarbook/
├── index.html     ← The entire app (single file!)
├── vercel.json    ← Vercel config
└── README.md      ← This file
```

## 🌐 Custom Domain (Optional)

1. In your Vercel project → **Settings → Domains**
2. Add your domain e.g. `udhaarbook.in`
3. Update your domain's DNS with the records Vercel shows you
4. Done in ~10 mins!

## 💡 Tips

- The app is a **PWA** — users can "Add to Home Screen" on mobile for an app-like experience
- All data is stored in the browser's **localStorage** — no backend needed for the free version
- For a real backend with MongoDB, the architecture is ready to plug in (Node.js + Express)

## 🔧 Local Development

Just open `index.html` in any browser — no build step needed!

```bash
# Or with a local server (recommended):
npx serve .
# Opens at http://localhost:3000
```

---

Made with ❤️ for small businesses everywhere.
