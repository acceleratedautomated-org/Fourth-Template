# 🚀 Deploy to Vercel

## Quick Deploy (Recommended)

### Option 1: Deploy from GitHub
1. Push your repo to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project" 
4. Import your GitHub repository
5. Vercel will auto-detect Vite and deploy!

Your site will be available at: `https://your-repo-name.vercel.app`

### Option 2: Deploy with Vercel CLI

1. Install Vercel CLI globally:
```bash
npm i -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy the project:
```bash
npm run deploy
```

## 🔧 Vercel Configuration

The project includes `vercel.json` with optimized settings:

- ✅ **Build Command**: `npm run build`
- ✅ **Output Directory**: `dist`
- ✅ **SPA Routing**: Configured for HTML pages
- ✅ **Auto-detection**: Vite framework

## 📁 Project Structure for Deployment

```
juno-watts/
├── public/           # Static assets
├── css/             # Stylesheets
├── script/          # JavaScript files
├── *.html           # HTML pages
├── package.json     # Dependencies
├── vercel.json      # Vercel config
└── vite.config.js   # Vite config (if needed)
```

## ⚡ Auto-deployment

Once connected to GitHub:
- **Every push** to main branch = automatic deployment
- **Pull requests** get preview deployments
- **Instant rollbacks** available

## 🌟 Custom Domain (Optional)

1. Go to your Vercel dashboard
2. Select your project
3. Go to "Settings" → "Domains"
4. Add your custom domain
5. Follow DNS configuration steps

---

**Need help?** Check [Vercel's documentation](https://vercel.com/docs) 📚
