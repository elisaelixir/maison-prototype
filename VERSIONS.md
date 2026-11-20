# Maison prototype: version history

Every version is kept in three ways:

1. **A live copy** you can open in the browser (the View links below).
2. **A Git tag** with the same name, so the code can be restored exactly.
3. **The full commit history** on `main`.

| Version | Date | What changed | Open |
| --- | --- | --- | --- |
| `v5-monochrome` | 2026-11-15 | The original monochrome dark workspace, before this redesign. | [View](https://elisaelixir.github.io/maison-prototype/versions/v5-monochrome/) |
| `v6-dark-refresh` | 2026-11-19 | First visual refresh: navy and sand-gold dark theme, bigger type, pill navigation, photo cards on home. | [View](https://elisaelixir.github.io/maison-prototype/versions/v6-dark-refresh/) |
| `v7-before-after-home` | 2026-11-19 | Rendy-inspired home: before/after hero (voice note to reel), live preview cards, scrolling app strip. Still dark. | [View](https://elisaelixir.github.io/maison-prototype/versions/v7-before-after-home/) |
| `v8-call-feedback-dark` | 2026-11-20 | Feedback from the 19 Nov call: home dashboard, unified leads inbox, video modes, carousels, winning ads, onboarding interview. Dark theme. | [View](https://elisaelixir.github.io/maison-prototype/versions/v8-call-feedback-dark/) |
| `v8-light` | 2026-11-20 | Same as v8 with the light theme (default) and a light/dark switch. | [View](https://elisaelixir.github.io/maison-prototype/versions/v8-light/) |
| `v9-motion` | 2026-11-20 | Lucide icons, smooth list changes, page entrances, scroll reveals, live hero demo, typed drafts. | [View](https://elisaelixir.github.io/maison-prototype/versions/v9-motion/) |
| `v10-calm-audit` | 2026-11-20 | avoid-ai-design audit: calmer, fewer stock effects, live activity on home. | [View](https://elisaelixir.github.io/maison-prototype/versions/v10-calm-audit/) |
| `v11-landing` | 2026-11-20 | Current: public landing page plus a lively portal home. | [View](https://elisaelixir.github.io/maison-prototype/versions/v11-landing/) |

The live site (https://elisaelixir.github.io/maison-prototype/) always shows the latest version. The portal is at `#portal`.

## Going back to an older version

- **Just to look:** open its View link above.
- **To make it the live site again:** copy `versions/<name>/index.html` over the root `index.html` and commit, or ask Claude to restore `<name>`.
- **From Git:** `git checkout <name> -- index.html` then commit.

When a new version ships, add a row here, a folder under `versions/`, and a tag.
