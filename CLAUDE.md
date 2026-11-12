# CLAUDE.md

The Danmaku Anywhere documentation site: Astro with Starlight, content in `src/content/docs/` (Chinese first). The extension's code lives in `Danmaku-Anywhere/danmaku-anywhere`.

- `pnpm build` runs `astro check` and the production build. Run it before opening a PR.
- Use pnpm, never npm or yarn. Run CLI tools with `pnpx`, not `npx`.
- Don't edit `src/content/docs/change-log.mdx` by hand. It is regenerated from the extension's releases by `scripts/sync-changelog.ts`; change the release notes instead.
- PR titles: `(docs) <description> [DA-XXX]`. Never put a `DA-XXX` id in the content or code.
- No em dashes (U+2014) in new text, in any language.
