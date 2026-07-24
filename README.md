# ReflexEdge — Landing Page

"Give Robots Reflexes." Marketing/landing page for ReflexEdge, a robot-native reflex
and black-box safety layer (event-based sensing + a separate trusted safety path).

Single self-contained file: `index.html` (no build step, no dependencies).

## Deploy

**Vercel:** `npx vercel --prod` from this folder (or import the repo at vercel.com/new).
**GitHub Pages:** push to a repo → Settings → Pages → deploy from `main` / root.
**Netlify Drop:** drag `index.html` onto https://app.netlify.com/drop for an instant URL.

## Wire up the pilot form (2 min)
In `index.html`, replace `FORM_ENDPOINT` with your Formspree/Tally/Google Form POST URL,
and swap the placeholder `founders@reflexedge.ai` for a real inbox. Until then the CTA
falls back to opening a pre-filled email.
