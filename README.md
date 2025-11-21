# AI Model Forge - Website

A modern, responsive one-page website for an AI model training company.

## 🚀 Deployment Options

### Option 1: GitHub Pages (FREE)

Your site will be available at: `https://vaibhav3m.github.io/work-website/`

**To enable:**
1. Go to your repository: https://github.com/Vaibhav3M/work-website
2. Click **Settings** → **Pages**
3. Under **Source**, select **GitHub Actions**
4. The GitHub Actions workflow will automatically deploy on push to `main` branch

**Custom Domain:**
1. In Settings → Pages, add your custom domain
2. Update your domain's DNS records as instructed
3. GitHub will automatically configure HTTPS

---

### Option 2: Vercel (RECOMMENDED - FREE & EASIEST)

**Why Vercel?**
- ✅ Easiest setup (2 clicks)
- ✅ Automatic HTTPS
- ✅ Custom domain support
- ✅ Global CDN
- ✅ Better performance than GitHub Pages

**Deploy:**
1. Go to https://vercel.com
2. Sign up/login with GitHub
3. Click **Add New Project**
4. Import your `work-website` repository
5. Click **Deploy** (no configuration needed!)
6. Your site will be live in ~30 seconds

**Custom Domain:**
1. In Vercel dashboard → Your Project → Settings → Domains
2. Add your custom domain
3. Update DNS records as shown
4. Automatic SSL certificate

**Your Vercel URL:** `https://work-website-*.vercel.app` (custom URL available)

---

### Option 3: Netlify (FREE)

**Why Netlify?**
- ✅ Drag-and-drop deployment
- ✅ Custom domain support
- ✅ Form handling (if needed later)
- ✅ Built-in analytics

**Deploy:**
1. Go to https://netlify.com
2. Sign up/login with GitHub
3. Click **Add new site** → **Import an existing project**
4. Select your `work-website` repository
5. Click **Deploy site**

**Custom Domain:**
1. In Netlify dashboard → Site settings → Domain management
2. Add custom domain
3. Update DNS records
4. Automatic HTTPS

**Your Netlify URL:** `https://work-website-*.netlify.app`

---

### Option 4: Cloudflare Pages (FREE)

**Why Cloudflare?**
- ✅ Fast global CDN
- ✅ Unlimited bandwidth
- ✅ Built-in analytics

**Deploy:**
1. Go to https://pages.cloudflare.com
2. Connect your GitHub account
3. Select `work-website` repository
4. Click **Begin setup** → **Save and Deploy**

---

## 📝 Custom Domain Setup

All platforms above support custom domains. Here's how:

1. **Buy a domain** (Namecheap, GoDaddy, Cloudflare, etc.)
2. **Add domain** in your hosting platform's settings
3. **Update DNS records:**
   - **Vercel/Netlify/Cloudflare:** Add CNAME or A records as shown
   - **GitHub Pages:** Add CNAME file to repository (they'll guide you)
4. **Wait for SSL:** Automatic HTTPS certificate (usually 5-60 minutes)

---

## 🔧 Local Development

```bash
# Start local server
python3 -m http.server 8000

# Or use Node.js http-server
npx http-server -p 8000
```

Visit: http://localhost:8000

---

## 📄 Edit Content

All content is in `config.json`. Edit it and push to update the website!

---

## 🎨 Features

- ✅ Fully responsive
- ✅ Modern SaaS design
- ✅ JSON-driven content
- ✅ No build process needed
- ✅ SEO optimized
- ✅ Fast loading

