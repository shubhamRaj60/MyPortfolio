# Deploy Your Portfolio to Vercel - Step by Step

## Prerequisites

- GitHub account (for easier deployment)
- Vercel account

## Step 1: Create a GitHub Repository

1. Go to https://github.com/new
2. Create a new repository named `portfolio` (or any name you prefer)
3. Add description: "My Professional Portfolio"
4. Select "Public" (so it's visible to employers)
5. Click "Create repository"

## Step 2: Push Your Portfolio to GitHub

### On Your Computer (Windows PowerShell):

```powershell
cd c:\Users\hp\Desktop\defence\portfolio

# Initialize git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial portfolio commit"

# Add GitHub as remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Deploy to Vercel

1. Go to https://vercel.com
2. Sign up with your GitHub account (if not already done)
3. Click "Add New..." → "Project"
4. Select your `portfolio` repository from the list
5. Click "Import"
6. Configuration will auto-detect:
   - Framework: Other (Static Site)
   - Root Directory: ./
7. Click "Deploy"
8. **Wait 2-3 minutes for deployment** ✅

## Step 4: Get Your Live URL

After deployment:

- Vercel will show your live URL (like: `https://portfolio-abc123.vercel.app`)
- This is your **public portfolio link**!
- Share this URL with employers, clients, etc.

## Step 5: Custom Domain (Optional)

To use a custom domain like `shubhamraj.com`:

1. In Vercel dashboard, go to your project
2. Settings → Domains
3. Add your custom domain
4. Follow DNS instructions from your domain provider
5. Domain will be live in 24-48 hours

## Quick Reference: Git Commands

```bash
# After making changes to your portfolio:
git add .
git commit -m "Updated portfolio"
git push

# Changes automatically redeploy to Vercel!
```

## Your Vercel Dashboard

- URL: https://vercel.com/dashboard
- View deployment logs
- See live analytics
- Manage custom domains

## Troubleshooting

**If deployment fails:**

1. Check that `index.html` exists in root directory ✅
2. All image/video files are in the same folder ✅
3. No broken links in HTML ✅
4. File permissions allow reading ✅

**If images don't load:**

- Verify all image paths in `index.html` are correct
- Use relative paths (not absolute paths)

## Performance Benefits

✅ Lightning-fast global CDN
✅ Automatic HTTPS/SSL
✅ Zero downtime deployments
✅ Analytics & insights
✅ Free tier for portfolio

## Next Steps After Deployment

1. **Share your portfolio link:**

   - LinkedIn profile
   - Resume
   - Job applications
   - Email signature

2. **Keep portfolio updated:**

   - Add new projects
   - Update certificates
   - Modify content
   - Just push to GitHub, Vercel auto-updates!

3. **Monitor performance:**
   - Check Vercel dashboard for analytics
   - View traffic and engagement

---

**Your portfolio deployment is now ready!**
Live URL will be: `https://portfolio-[random].vercel.app`

Need help with any step? Let me know!
