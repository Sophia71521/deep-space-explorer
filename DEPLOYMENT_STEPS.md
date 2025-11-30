# Deploy Deep Space Explorer to Vercel

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `deep-space-explorer`
3. Make it Public
4. **DO NOT** check "Add a README file" (we already have one)
5. Click "Create repository"

## Step 2: Push to GitHub

After creating the repo, GitHub will show you commands. Copy YOUR repository URL and run:

```bash
cd "c:\Users\Sophia\Desktop\Portfolio\Space Website"
git remote add origin https://github.com/YOUR_USERNAME/deep-space-explorer.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 3: Deploy to Vercel

### Option A: Import from GitHub (Recommended)

1. Go to https://vercel.com/
2. Sign in (or create account using GitHub)
3. Click "Add New..." → "Project"
4. Click "Import" next to `deep-space-explorer`
5. Framework Preset: **Other** (it's just HTML)
6. Click "Deploy"
7. Wait 30-60 seconds
8. Done! You'll get a URL like: `https://deep-space-explorer.vercel.app`

### Option B: Deploy with Vercel CLI

If you prefer command line:

```bash
# Install Vercel CLI globally
npm install -g vercel

# Navigate to project
cd "c:\Users\Sophia\Desktop\Portfolio\Space Website"

# Deploy
vercel

# Follow prompts:
# - Login with GitHub
# - Link to existing project or create new
# - Accept default settings
# - Done!
```

## Step 4: Update Portfolio Link

Once deployed, you'll get a URL like:
`https://deep-space-explorer.vercel.app`

Copy that URL and I'll update your portfolio's project link!

---

## Your Vercel URL will be here:

Once deployed, write it down:

```
https://__________________________.vercel.app
```

Then tell me the URL so I can update your portfolio!
