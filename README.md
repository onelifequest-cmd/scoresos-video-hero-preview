# Score OS homepage — full-screen video hero (PREVIEW)

Static preview only. **Do not deploy to or change live scoresos.com.**

- Local path: `/workspace/projects/scoresos-homepage/video-hero-preview/`
- noindex + `robots.txt` Disallow
- Placeholder film: `media/hero-placeholder.{mp4,webm}` + `media/hero-poster.jpg`
- Swap in Patrick's real video where the HTML comment says `REAL VIDEO SWAP`

## Links (confirmed against live SPA bundle)

| Label   | URL |
|---------|-----|
| Login   | https://scoresos.com/login |
| Pricing | https://scoresos.com/#pricing |
| Info    | https://scoresos.com/#about |

Notes: `/plans` is owner-auth only (redirects to billing). `/scoreos` is the admin Console. `/for-clients` is the consumer page. Outsourcer login is `/outsourcer/login` (not in this top bar).

## Hosting

Same pattern as earlier Scores/Conquest previews: public GitHub repo + Render static site (`onrender.com`), free, noindex.
