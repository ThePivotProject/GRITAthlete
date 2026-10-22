# GRIT Athlete Portfolio - GitHub Pages Deployment

## Files included:
- index.html - Main app (The GRIT Athlete Portfolio)
- manifest.json - PWA manifest
- icon-192.png, icon-512.png, apple-touch-icon.png, icon.png - App icons
- .nojekyll - Tells GitHub Pages to not use Jekyll (fixes black screen)

## Deploy to GitHub Pages:

1. Create a new GitHub repository (or use existing)
   - Name it e.g. `grit-portfolio` or `your-username.github.io` for user site

2. Upload all files to the repository root:
   - Go to your repo on GitHub
   - Click "Add file" -> "Upload files"
   - Drag all files from this folder (index.html, manifest.json, icons, .nojekyll)
   - Commit

3. Enable GitHub Pages:
   - Go to repo Settings -> Pages (on left sidebar)
   - Under "Build and deployment", set Source to "Deploy from a branch"
   - Select Branch: main (or master) and folder: / (root)
   - Save

4. Wait 1-2 minutes, then visit your site:
   - https://your-username.github.io/repo-name/
   - Or https://your-username.github.io/ if using user site

5. If you see black screen:
   - Hard refresh: Cmd+Shift+R (Mac) or Ctrl+Shift+R (Windows)
   - Open console: Cmd+Option+J (Mac) or Ctrl+Shift+J (Windows) to see errors
   - Make sure .nojekyll file is in repo root

## Local testing:
- Double-click index.html to open locally in browser
- Should show "We Are Built" footer, GRIT Training Program, etc.

## What's in this version:
- Training page: "Your GRIT Training Program" with "30 Minutes is being slightly motivated..." subtitle
- Physical and Mindset boxes editable at top of Training
- PR page: D1 softball metrics (20-Yard 2.85 sec, Vertical 24 in, Home to First 2.75 sec, etc.)
- PR example: Pitch Velocity 59-65 MPH (not Back Squat)
- GRIT Level: "Your GRIT Level" with new explanation about consecutive weeks
- Quote: "Until death, all defeat is psychological" - Marcus Aurelius
- Load Athlete button at top of Athlete Profile page
