# Web Tech Final Revision

Single-page revision sheet for **CSC 3222 Web Technologies** (AIUB), final term.

Three tabs:
- **Q6** — Club Membership: MVC structure, prepared statements, radio/select/checkbox, session vs cookie, superglobals
- **Q7** — Output tracing: six PHP programs unrolled one pass at a time
- **Theory** — ten short-answer questions with model answers

Everything is one static `index.html`. No build step, no dependencies.

## Deploy to Vercel

```bash
npm i -g vercel     # once
cd vercel-revision
vercel              # preview URL
vercel --prod       # production URL
```

Or drag this folder onto https://vercel.com/new.

## Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
