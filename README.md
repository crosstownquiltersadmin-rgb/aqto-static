# aqto-static

Static version of the Crosstown Quilters Guild site, adapted from an AQTO managed export.

## What changed
- Removed all AQTO runtime JavaScript dependencies
- Kept the visual layout and CSS
- Added placeholder pages for navigation links
- Configured for Cloudflare Workers static assets via `wrangler.jsonc`

## Deploy to Cloudflare
1. Connect this repo to a Cloudflare Worker
2. Set the deploy command to `npx wrangler deploy`
3. Assets are served from the `public/` directory

The original AQTO export is preserved in spirit but is now a pure static site with no external runtime dependencies.
