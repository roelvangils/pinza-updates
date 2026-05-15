# pinza-updates

Public Sparkle feed for [Pinza](https://github.com/roelvangils/pinza)
(the source repo is private). Files here are generated automatically
by Pinza's release script — don't edit by hand.

- `appcast.xml` — Sparkle 2 feed consumed by Pinza's in-app updater.
- `release-notes/<version>.html` — per-release notes rendered from
  the GitHub Release body. Sparkle's update dialog loads these
  inline before the user installs.
- `.nojekyll` — disables Jekyll preprocessing so the HTML notes
  serve as-is.

Live at <https://roelvangils.github.io/pinza-updates/appcast.xml>.
