# UUM CGPA Calculator

A sleek CGPA calculator built for Universiti Utara Malaysia students, using the UUM grading system.

## Features
- Add multiple semesters and subjects
- UUM grading scale (A = 4.00, A- = 3.67 ... F = 0.00)
- Live CGPA calculation
- Include previous academic record for cumulative GPA
- Honours classification display (First Class, Second Upper, etc.)
- Collapsible semesters

## Deploy to Vercel

### Option 1: Vercel CLI (recommended)
```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to project folder
cd uum-cgpa-calculator

# Deploy
vercel

# Follow the prompts — it auto-detects static HTML
# Your site URL will be shown at the end
```

### Option 2: Vercel Dashboard (drag & drop)
1. Go to [vercel.com](https://vercel.com) and sign in (free account)
2. Click **"Add New Project"**
3. Drag and drop this entire `uum-cgpa-calculator` folder into the import box
4. Click **Deploy**
5. Done! Your calculator is live 🎉

### Option 3: GitHub + Vercel (auto-deploy on push)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select the repo → Deploy
4. Every `git push` will auto-redeploy
