---
name: Dependency upgrades
schedule: 0 5 * * 1
---

Bring the dependencies in this repository up to date, majors included, and open pull requests. Never merge them.

Check open dependency pull requests first and update them instead of opening duplicates. Skip versions released less than 3 days ago and never move a stable version onto a prerelease. Put patch and minor bumps into one pull request, and give each major bump its own. For breaking upgrades, follow the migration guide and fix the code properly rather than pinning back or adding workarounds. Run whatever checks the project has before pushing, and describe each change and how any breakage was handled in the pull request.

Finish with a short summary of pull requests opened or updated, and packages skipped with the reason. If nothing is outdated, say so in one line.
