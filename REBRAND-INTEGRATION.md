# VELRUNE STUDIO — Website Rebrand Integration

This development branch preserves the existing Excite I Once A–Z gallery and its original artwork. It is **not** the Cloudflare production branch.

## Approved brand specifications
- Primary logo: user-supplied `Blue Minimalist Studio Logo.png` (original PNG, not a recreated wordmark).
- Palette: burnt orange `#E08B2F`, charcoal `#3F4142`, warm ivory `#F3EFE1`.
- Fonts: Oswald headings, Space Grotesk interface and body.
- Visual style: cinematic editorial layout, responsive design, restrained motion.
- Project: Excite I Once A–Z illustration gallery with scroll-triggered bounce and reduced-motion fallback.

## Preserve on migration
- Domain: `velrunestudio.com`.
- Business email: `hello@velrunestudio.com`.
- Existing social and contact links.
- Existing Zoho Mail DNS configuration.

## Deployment boundary
Cloudflare currently deploys `paddy321/creative-portfolio` from `main` using `npx wrangler deploy`. This repository is a separate website source. Do not switch Cloudflare's connected repository or merge to production until the full website, assets, build configuration and routes are verified.

## Existing project page
`work/excite-a-z.html` is the alphabet gallery. Its original illustrations are referenced under `assets/alphabet/`.

## Remaining integration checks
1. Verify homepage, navigation, logo asset, font files, project links and all 26 images.
2. Ensure project page is linked from Work and accessible by keyboard.
3. Validate mobile and reduced-motion behavior.
4. Stage a Cloudflare-compatible deployment and check it before switching production.
