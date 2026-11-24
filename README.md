# Instagram Creator Niche Map — by Sifu Yik

Instagram version of https://niche.sifuyik.com/ (source: github.com/yncacademy/niche)

## Files
- `index.html` — the whole site, single file, no build step. Same design, fonts, search, category chips, and Copy angle buttons as the Facebook version.
- `CNAME` — contains ig.sifuyik.com
- `facebook-index.html` — original Facebook source, kept for reference only. Do not deploy this one.

## Content
- 32 categories / lanes
- 377 niches, each with a one-line Instagram content angle (Reel, carousel, or photo post)
- Source list: Social Blade Instagram classifications, cleaned (no Gold / Silver tiers). "All Categories" was dropped — it is a filter, not a niche.

## Domain
- ig.sifuyik.com — `CNAME` file is included with this value.
- Theme: Instagram gradient (purple #833ab4 / purple-pink #962fbf, pink #d62976, orange #fa7e1e / #f77737, yellow #feda75, blue-purple #4f5bd5) instead of the Facebook version's green.

## Deploy (same as the Facebook site)
1. Create a new GitHub repo, e.g. `instagram-niche`
2. Upload `index.html` and `CNAME` to the repo root
3. Enable GitHub Pages on the repo (main branch, root)
4. Point the `ig` subdomain's DNS CNAME to `<your-github-username>.github.io`

## Still to decide
- Instagram Training date/time — the site currently says "Coming soon" in the training section, with the link dropping on Substack, same as the Facebook version's pattern
