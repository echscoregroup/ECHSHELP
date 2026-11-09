# BUILD 1.0.5 — PRODUCTION MIRROR

**Purpose:** Controlled testing copy of the user-facing production website.

**Starting point:** `echscoregroup/ECHSHELP`, branch `main`.

**Production reference:** Build 1.0, launched on **5 November 2026**.

**Build label in this branch:** `1.0.5`.

This branch was created from the production `main` branch as it existed at the time the branch was created. The website files and published content, including `news.md`, were copied from that production starting point. The only initial application-file change is the build identification marker in `index.html`, which labels this controlled test copy as Build 1.0.5.

## Testing purpose

Use this branch to test the website before considering any change for production, including:

- Video Library and category navigation
- Situation–Solution content and links
- News display, including visibility of a newly added news item
- PDFs, downloads, and external links
- Mobile and desktop layout and navigation
- Any other existing website features

## Production protection

- This is a test branch, not the production release.
- Do not make test changes directly in `main`.
- Do not merge or copy changes to `main` unless the owner explicitly approves.
- After the tests pass, use this branch as the verified working basis for proposed changes. Test each proposed change here first, then perform a quick production-release check before any separately approved update to `main`.

**Production URL:** https://echscoregroup.github.io/ECHSHELP/

**Test branch:** `BUILD-1.0.5-PRODUCTION-MIRROR-05NOV2026`
