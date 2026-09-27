# site — smart-notes.org

Static pages the App Store listing links to: privacy policy, terms and
support. Plain HTML, no build step. Published by Cloudflare Pages from `main`.

| URL | File |
|---|---|
| `/privacy/` | `privacy/index.html` — App Store «Privacy Policy URL» |
| `/support/` | `support/index.html` — App Store «Support URL» |
| `/terms/` | `terms/index.html` |

## Cloudflare Pages settings

- Framework preset: **None**
- Build command: *(empty)*
- Build output directory: `site`
- Production branch: `main`
- Custom domain: `smart-notes.org` (and `www.smart-notes.org`)

## Keep in sync

The in-app legal texts live in `frontend/src/shared/i18n/{ru,en}.ts`
(`legal.*`). When a policy changes, update both places and the date.
