# Static Files • Dynamic Experiences

Interactive single-file website explaining static and dynamic hosting.

## Cloudflare Workers deployment

- Static files: `public/index.html`
- Worker configuration: `wrangler.jsonc`
- Build command: leave blank
- Deploy command: `npx wrangler deploy`
- Root directory: `/`

A push to `main` can trigger Cloudflare Workers Builds automatically after GitHub integration is configured.
