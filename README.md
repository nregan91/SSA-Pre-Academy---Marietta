# SSA Swarm FC — Pre Academy Training Plan (Fall 2026)

A single-page, parent- and coach-facing training plan for the SSA Swarm FC Pre Academy (ages 4–7), Marietta.

- **12-week season**, one topic per week (Dribbling · Passing · Shooting · Games & Shape), rotating in order.
- **Separate Monday & Wednesday sessions** each week — no repeated drills.
- Every session: a **4-grid rotation board** (Coach 1–4 with named pairs), Ball Mastery warm-up, four stations with **field diagrams + demo videos**, and **5v5/6v6 small-sided games**.
- Built for **~11 players per grid, maximum touches** (line drills capped at 3 per line).
- Branded to match the SSA Swarm FC app.

## The site

Everything is in **`index.html`** — a self-contained static page (no build step, no dependencies to install; fonts load from Google Fonts, demo links go to YouTube).

## Deploy (Vercel)

**CLI:**
```bash
npx vercel --prod
```

**Or GitHub import:** at vercel.com → Add New → Project → import this repo → Framework preset **Other** → Deploy. Pushes to `main` auto-deploy.

To make it public: Vercel project → Settings → Deployment Protection → set **Vercel Authentication** to Disabled.
