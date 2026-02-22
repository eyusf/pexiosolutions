# Pexio Solutions — Website

Official marketing website for **Pexio Solutions**, a digital growth agency building websites, apps, and digital strategies.

## 🚀 Deployment

This site is hosted via **GitHub Pages** with a custom domain.

**Live site:** [www.pexiosolutions.com](https://www.pexiosolutions.com)

---

## 📁 File Structure

```
pexio-solutions/
├── index.html      # Main website
├── CNAME           # Custom domain config for GitHub Pages
└── README.md       # This file
```

---

## 🌐 Custom Domain Setup (Step-by-Step)

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pexio-solutions.git
git push -u origin main
```

### 2. Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**

### 3. Configure Your Custom Domain (DNS Settings)
Log into your domain registrar (GoDaddy, Namecheap, Cloudflare, etc.) and add these DNS records:

| Type  | Host | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | YOUR_USERNAME.github.io |

> Replace `YOUR_USERNAME` with your actual GitHub username.

### 4. Set Custom Domain in GitHub Pages
1. In **Settings → Pages**, enter `www.pexiosolutions.com` in the **Custom domain** field
2. Click **Save**
3. Check **Enforce HTTPS** once DNS propagates (can take up to 48 hours)

---

## ✅ Done!

Once DNS propagates, your site will be live at `https://www.pexiosolutions.com`.
