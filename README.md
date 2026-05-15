# Nook Journal

Nook Journal is an editorial publication concept for issue pages, story cards, content models, archive patterns, and a refined reading experience.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://nookjournal.blog/](https://nookjournal.blog/)
- Source: [https://github.com/wix-incubator/nookjournal](https://github.com/wix-incubator/nookjournal)
- Wix site ID: `909bfb07-886f-4451-a042-0d2df40ed592`

## What It Showcases

- A custom Astro editorial interface on a Wix Headless foundation.
- A CMS-style content model for essays, guides, interviews, and resource lists.
- A publication front door that could be wired to Wix CMS collections.
- Reusable story metadata and archive patterns.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix CMS as the intended content solution demonstrated by the editorial model and page structure.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`

This repo currently demonstrates the CMS-facing UX and Headless site foundation. It does not yet contain direct `@wix/data` collection reads.

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
