# Lab — Post-train self-improving agents

Static site from the HTML prototype. Deploy the `public/` directory to Cloudflare Pages; no build step is needed.

All external page assets are in `public/assets/`.

Live site: https://lab-post-train-agents.pages.dev/

To publish updates:

```sh
npx wrangler pages deploy public --project-name lab-post-train-agents --branch main
```
