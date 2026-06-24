# PK Works — One-Page Site

A self-contained marketing site. No build step, no dependencies. Just `index.html`.

## Edit
Open `index.html` in any editor. Everything (copy, prices, colors) is inline near the top in the `<style>` block and the page body. No framework to learn.

Key things you'll likely want to change:
- Email address: search for `phil@pkworks.co` and replace everywhere (currently in the nav CTA target, contact button, and footer area).
- Prices / package details: in the `services` and `apps` sections.
- The "About" copy and stats.

## Deploy to Vercel (same as your other projects)
Option A — drag and drop:
1. Go to vercel.com, "Add New… → Project".
2. Drag this whole folder in, or connect a GitHub repo containing these files.
3. Framework preset: "Other". No build command. Output directory: leave as root.
4. Deploy. Point your pkworks domain at it in the Vercel domain settings.

Option B — CLI:
```
npm i -g vercel
cd pkworks-site
vercel
```

## Files
- `index.html` — the entire site
- `vercel.json` — clean URL config
- `pk-logo.png` / `pk-logo-white.png` — your logo, kept here for favicon or future use
