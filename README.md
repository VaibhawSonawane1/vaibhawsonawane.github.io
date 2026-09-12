# Vaibhaw Sonawane — Portfolio

A React portfolio site styled as an API reference / terminal, built from your resume content.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL Vite prints (usually http://localhost:5173).

## Build for production

```bash
npm run build
```

Output goes to `dist/` — deploy that folder to Vercel, Netlify, GitHub Pages, or any static host.

## Resume download button

`public/resume.pdf` already has your resume in it — the "download resume" buttons in the hero and contact section link straight to it. To swap in a newer version later, just replace `public/resume.pdf` with the new file (keep the same filename, or update the `href` in `App.jsx`).

## Edit your content

Everything lives in `src/App.jsx`:
- `experience` — jobs and sub-projects
- `skillGroups` — skill categories and tags
- `education` — degrees
- `certifications` — cert list
- Contact section near the bottom — update the LinkedIn and GitHub links (currently placeholders)

## Stack

- React 18 + Vite
- lucide-react icons
- No CSS framework — plain CSS embedded in `App.jsx`, so nothing extra to configure
