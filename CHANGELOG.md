# Changelog

Upstream Next.js release notes are published at [github.com/vercel/next.js/releases](https://github.com/vercel/next.js/releases).

## v27.26102701 - 2026-10-27

### Changes since v16.4.0-canary.58

- Fixed the App Router navigation queue to publish completed navigation state before it runs the next queued action (`packages/next/src/client/components/app-router-instance.ts`).
- Added `ZUKUJS.md` and `zukujs-version.json` to declare the ZukuJS fork identity, upstream base, and protocols.
- Added the ZUKU logos and bilingual brand guidance in `docs/branding/`, and the ZUKU brand header in the root README.
- Resolved the README logo URLs so that they load from both the repository root and the `packages/next` README.
