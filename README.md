# addmore docs

Public documentation site for [addmore.studio](https://addmore.studio), built on
[Mintlify](https://mintlify.com). Content lives in `.mdx` files; site config,
navigation, and branding live in `docs.json`.

> **Status:** Setup + styling with placeholder content. Real copy and final
> information architecture are still to come.

## Editing

- **Non-technical:** edit in the Mintlify web editor — changes sync back as
  commits to this repo.
- **Technical:** edit the `.mdx` files and `docs.json` directly.

Deploys happen automatically when changes reach `main`.

## Local preview

```bash
npm i -g mint
mint dev
```

Opens a live preview at http://localhost:3000.

## Structure

| Path | What it is |
| --- | --- |
| `docs.json` | Site config: nav, theme, colors, fonts, logo, favicon |
| `custom.css` | Minimal CSS overrides (currently just ABC Diatype tracking) |
| `*.mdx` | Documentation pages |
| `project-phases/` | Grouped phase pages |
| `logo/`, `fonts/`, `favicon.png` | Branding assets |

## Branding

Colors and the ABC Diatype font come from the addmore design system
(`addmore-studio/addmore-design-system`, `packages/tokens`) — values copied by
hand, no packages installed.
