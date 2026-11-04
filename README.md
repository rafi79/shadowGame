# The Shadow Files: AI Crime Investigation

A browser-based detective adventure game that teaches AI security:
prompt injection, excessive agency, deepfakes, data poisoning, and more.

It is a single static page (`index.html`). There is no build step and no server code.

## Deploy to Vercel

### Option A: Vercel dashboard (no coding)
1. Push this folder to a GitHub repository.
2. Go to https://vercel.com/new and import the repository.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Click **Deploy**.

### Option B: Vercel CLI
```bash
npm i -g vercel
cd shadow-files-vercel
vercel          # preview deployment
vercel --prod   # production deployment
```

## Run locally
Open `index.html` in any browser, or run:
```bash
npx serve .
```

## Notes
- Fonts load from Google Fonts, so an internet connection is needed for the best look.
- Progress is saved in the player's browser (localStorage) after each case is closed.
- Instructor tip: the secret vault code is 731.
