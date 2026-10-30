# VOYAGE — Clean Version (Correct Business Logic)

> **"Go places. Feel everything."**
> Production-ready verified version of Voyage travel reservation platform with zero defects, accurate date checks, transparent 12% GST, and strict room inventory locking.

---

## Environment: Production / Verified Logic

This repository contains the standalone, independent build of **VOYAGE** configured specifically for **voyage-clean-version**.

---

## Quick Deploy to Vercel

### Option 1: Via GitHub & Vercel Dashboard (Easiest)
1. Create a new repository on your GitHub account named `voyage-clean-version`.
2. Push this directory to your new GitHub repo:
   ```bash
   git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/voyage-clean-version.git
   git branch -M main
   git push -u origin main
   ```
3. Go to [https://vercel.com/new](https://vercel.com/new), select your `voyage-clean-version` repository, and click **Deploy**.
4. Vercel will automatically detect Vite and deploy your site in seconds!

### Option 2: Via Vercel CLI
```bash
npx vercel
# Follow the prompts and accept defaults (Vite Framework Preset)
```

---

## Local Development

```bash
# Install dependencies
npm install

# Start local development server
npm run dev

# Build production bundle
npm run build

# Preview production build locally
npm run preview
```
