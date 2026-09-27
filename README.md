# screen-notes-page — smart-notes.org

Static pages the App Store listing links to: privacy policy, terms and
support. Plain HTML, no build step. Published by Cloudflare Pages from `main`.

| URL | File |
|---|---|
| `/privacy/` | `privacy/index.html` — App Store «Privacy Policy URL» |
| `/support/` | `support/index.html` — App Store «Support URL» |
| `/terms/` | `terms/index.html` |

Links between pages are root-relative (`/styles.css`, `/privacy/`), so the
repository root must be the site root.

## Cloudflare Pages settings

- Framework preset: **None**
- Build command: *(empty)*
- Build output directory: `/` (repository root)
- Production branch: `main`
- Custom domain: `smart-notes.org` (and `www.smart-notes.org`)

## Keep in sync

The same legal texts are shown inside the app: `Sodaaffected/screen-notes`,
`frontend/src/shared/i18n/{ru,en}.ts` (`legal.*`). When a policy changes,
update both repositories and the date.
