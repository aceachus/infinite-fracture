# Infinite Fracture: the public site

The small public website for **Infinite Fracture** (iOS), served by GitHub Pages from `main` at
**https://aceachus.github.io/infinite-fracture/**.

| Path | Page |
| --- | --- |
| `/` (`index.html`) | landing page |
| `/privacy/` (`privacy/index.html`) | the privacy policy, which the game links to (Settings > Data > Privacy) and App Store Connect's privacy URL points at |
| `/support/` (`support/index.html`) | support: reporting a bug, the contact email, deleting your data |

`style.css` is shared by all three pages. Plain HTML, no build step.

The policy describes the game's analytics and bug reports. Its facts (what is collected, the 12-month
retention, the consent prompt, Delete my data) come from the game repo's `docs/analytics.md` and
`docs/bug-report.md`. Change both together, and update the "Last updated" date.

This repo was `infinite-fracture-privacy` (a single policy page) until 2026-10-03.
