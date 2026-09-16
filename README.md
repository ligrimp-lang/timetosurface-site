# timetosurface-site

The landing, privacy and support pages for **Time to Surface**, the technical dive planner
for iPhone. Served by GitHub Pages from `main` / root — the same arrangement as
`turnpressure-site`.

- <https://ligrimp-lang.github.io/timetosurface-site/>
- <https://ligrimp-lang.github.io/timetosurface-site/privacy.html>
- <https://ligrimp-lang.github.io/timetosurface-site/support.html>

The privacy policy and support URLs are required by App Store Connect and are referenced
from the app's store listing. **They must not 404** — Apple rejects a submission for a dead
privacy-policy URL.

## This folder is the source — the GitHub repo is a publishing target

The pages live in the `turn_pressure` repository, at `timetosurface-site/`, and moved there
on 2026-08-26 because no project file lives outside the project folder. Edit them here;
`ligrimp-lang/timetosurface-site` is only where they get published to.

    .claude/skills/ship/scripts/publish-site.sh time-to-surface --dry-run   # what would change
    .claude/skills/ship/scripts/publish-site.sh time-to-surface             # commit and push

It refuses to publish uncommitted changes, so what is on the web always names a commit in
the project repository.

Contact: timetosurface@ismailov.net

© 2026 Rustam Ismailov
