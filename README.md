# CLASSVERSE ULTRA 3D

Interactive virtual school campus with real Three.js WebGL, click-to-explore buildings, timetable, quotes, task tracker, and responsive futuristic interface.

## Files
- `index.html` — semantic page structure
- `style.css` — all layouts, UI effects, animations, mobile rules
- `script.js` — 3D world, interactions, timetable, quotes, local storage

## Run locally
Open folder in VS Code and launch `index.html` with **Live Server**. An internet connection is required to load Three.js and Google Fonts from CDN. Use a modern browser with WebGL enabled.

## GitHub Pages
1. Create public repository `classverse-ultra-3d`.
2. Upload all three files to the repository root.
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/(root)` → Save.
4. Open `https://USERNAME.github.io/classverse-ultra-3d/` (replace USERNAME).

## Customize
- Edit `timetable` in `script.js` to set real subjects and lesson times.
- Edit `quotes` to change daily inspiration.
- Edit `info` to adjust the description of clickable campus locations.
- Edit links in `index.html` to add your own resources.
- Change `--accent` in `style.css` for your preferred accent color.

## Important
The schedule is sample data, not connected to Kundelik. Tasks are stored in each browser's localStorage (not shared across students). This is a front-end MVP with procedural 3D geometry, not a multi-user school management system.
