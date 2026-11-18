# Alqurmanix AQX — Main Website

Starter repository for the AQX main website, deployed with Cloudflare Workers Static Assets.

## Structure

- `public/`: static website files
- `src/index.js`: Worker entry point and response security headers
- `wrangler.jsonc`: Cloudflare Workers configuration

## Preview safety

This is a temporary preview. The page includes `noindex,nofollow`, and `robots.txt` blocks crawling. Before public launch, replace the placeholder content, remove the `noindex` directive, and publish a production sitemap and robots policy.

## Deploy

Deploy using Wrangler:

```sh
npx wrangler deploy
```

No API keys, passwords, or private credentials belong in this public repository.
