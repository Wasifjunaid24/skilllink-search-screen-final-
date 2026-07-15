# SkillLink — Project Search Screen

A responsive HTML + Tailwind CSS implementation of the Project Search screen
from the SkillLink Figma design (Q7).

## Run locally
Just open `index.html` in a browser — styles are pre-compiled into `dist/output.css`,
no build step needed to view it.

## Rebuild CSS after editing index.html
```
npm install
npx tailwindcss -i src/input.css -o dist/output.css --minify
```

## Deploy (pick one)
- **Netlify Drop**: go to https://app.netlify.com/drop and drag this whole folder in.
  Gives you a live URL in ~10 seconds, no account required.
- **Vercel**: `npx vercel` from this folder (follow prompts).
- **GitHub Pages**: push this folder to a repo, enable Pages on the `main` branch.

Breakpoints tested: 375px (mobile) and 1280px (desktop).
