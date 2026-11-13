# Handoff: tresmonoscapital.github.io (tresmonos.capital)
Last updated: 2026-11-13. Written from the repo on `main`. No CLAUDE.md or README exists.

## Current goal
A single-page marketing site for a seed-stage venture firm: hero, beliefs, quote, portfolio, team, pitch. Anything beyond keeping it live: unknown.

## Where things stand
- Live on GitHub Pages from `main` (root), custom domain via `CNAME`. Push to `main` deploys.
- Recent work, newest first: source photos added; favicon and og-image; SEO pass (structured data, `robots.txt`, `sitemap.xml`, Twitter card); a portfolio company added; black-and-white contrast tuning on the team headshots.
- Nothing uncommitted visible.

## Workspace state
- `index.html` is the whole site: styles and script inline, no build, no dependencies to install.
- Assets at root: `team-*.jpg` (B&W headshots), `favicon.svg`, `og-image.png`.
- Canonical URL is the custom domain; keep `index.html`, `sitemap.xml` and `robots.txt` consistent if the domain changes.
- Run: open `index.html` in a browser, or `python3 -m http.server`.

## Rules visible in the repo
- Team photos are matched in contrast on purpose (several tuning commits); re-balance by eye when swapping a photo.
- Portfolio count in the copy is hand-edited alongside the list (commit `c131b79` bumped both).

## Verification
No tests or checker. After a deploy, load the live domain and confirm the page, `/robots.txt` and `/sitemap.xml` respond.

## Open questions
- Who maintains the content and how often: unknown.
