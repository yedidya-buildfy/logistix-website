# Logistix Marketing Website

A standalone marketing website for the Logistix Shopify app.

## 🚀 Features

- **Dark Mode Design** - Clean, modern dark theme
- **Responsive** - Works on all devices
- **Pure HTML/CSS** - No frameworks or build tools needed
- **Fast Loading** - Minimal code, maximum performance

## 📁 Files

- `index.html` - Main page structure
- `style.css` - Dark mode styles
- `README.md` - This file

## 🌐 Deployment Options

### Option 1: Netlify (Recommended - Free)
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
cd Logistix-website
netlify deploy --prod
```

### Option 2: Vercel (Free)
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
cd Logistix-website
vercel --prod
```

### Option 3: GitHub Pages (Free)
1. Create a new GitHub repository
2. Push this folder
3. Enable GitHub Pages in Settings → Pages
4. Your site will be at: `https://username.github.io/repo-name/`

### Option 4: Render Static Site (Free)
1. Push to GitHub
2. Create new "Static Site" on Render
3. Connect repository
4. Set publish directory to `Logistix-website`

## 🔧 Customization

Before deploying, update the install URL in `index.html`:

Replace `https://your-app.onrender.com/auth` with your actual app URL.

## 📝 Content Updates

To modify content, edit `index.html`:
- **Hero text**: Lines 12-14
- **Features**: Lines 24-67
- **How it works**: Lines 78-103
- **Use cases**: Lines 114-137

## 🎨 Style Updates

To modify colors/design, edit `style.css`:
- **Main gradient**: Line 21 (hero background)
- **CTA button**: Line 49 (button gradient)
- **Background**: Line 11 (body background)
- **Card colors**: Line 97 (feature cards)
