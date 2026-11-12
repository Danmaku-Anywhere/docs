# Danmaku Anywhere docs

The documentation site for [Danmaku Anywhere](https://github.com/Danmaku-Anywhere/danmaku-anywhere), built with Astro and Starlight and served at https://danmaku.weeblify.app from the `danmaku-anywhere-docs` Cloudflare Worker.

```sh
pnpm install
pnpm dev     # local site
pnpm build   # astro check, then the production build in dist/
```

Cloudflare builds a preview for every PR and deploys `master`.

The changelog page (`src/content/docs/change-log.mdx`) is generated from the extension's GitHub releases. A daily workflow regenerates it and opens a PR when it changed; run `pnpm sync-changelog` to do the same locally.
