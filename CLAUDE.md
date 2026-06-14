# BransonBlastUSA — Project Context for Claude

## Project Overview
- **Site:** BransonBlastUSA.com — Branson, Missouri travel guide and attraction directory
- **Tech Stack:** Vanilla HTML + CSS (`styles.css`) + JS (`script.js`), no build step
- **Deployment:** Cloudflare Pages, connected to this GitHub repo (`main` auto-deploys)
- **Domain:** bransonblastusa.com (Cloudflare managed)

## Project Structure
- `index.html` — homepage
- `styles.css` — global stylesheet
- `script.js` — site JavaScript
- `robots.txt`, `sitemap.xml` — SEO files
- `_headers` — Cloudflare Pages security headers
- `_redirects` — Cloudflare Pages URL redirects
- `404.html` — custom error page
- `avatar/` — avatar/image assets
- `videos/` — video assets
- **Content pages:** branson-lakes-area-guide.html, branson-weekend-trip-ideas.html, branson-west-visitor-guide.html, lake-taneycomo-fishing-trip.html
- **Utility pages:** advertise-branson.html

## Git Workflow
- `main` branch auto-deploys to Cloudflare Pages
- Feature branches: `feature/branch-name` or `claude/...`
- Follow Conventional Commits: `feat:`, `fix:`, `chore:`, `docs:`

## Important Rules
- No frameworks — pure HTML/CSS/JS only
- Mobile-first design
- All pages must have `<title>`, `<meta description>`, and be listed in `sitemap.xml`
- No unsupported claims about attractions or events without sourcing
