# Nutrition & Muscle Goal Calculator (No-Build, GitHub Pages Ready)

A single-file React app to estimate **BMR, TDEE, daily calories, and macros** for fat loss, maintenance, or muscle gain.  
It also includes **Copy summary**, **Download CSV**, and a **Permalink** you can share.

## Quick Start (GitHub Pages)
1. Create a new repo on GitHub (e.g. `nutrition-calculator`).
2. Upload `index.html` to the repo root.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**.  
   - Branch: `main` (or `master`)  
   - Folder: `/ (root)`
4. Save. GitHub Pages will give you a URL in a minute or two.

## Local Use
Just open `index.html` in a browser. No build step needed.

## How It Works
- **BMR**: Mifflin–St Jeor equation
- **TDEE**: `BMR × activity factor`
- **Targets**: Lose = `TDEE × 0.80`, Gain = `TDEE × 1.15`, Maintain = `TDEE`
- **Macros**: Protein `1.6–2.0 g/kg`, Fat `0.8 g/kg`, Carbs = remaining calories

> These are starting points. Track progress 1–2 weeks, then adjust by 5–10%.
