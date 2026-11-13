---
name: release-notes
description: Drafts customer-facing release notes from merged PRs. Use when the user asks for release notes, a changelog entry or a "what's new" summary.
---

# Team release notes

1. List the commits since the last tag: `git log $(git describe --tags --abbrev=0)..HEAD --oneline`.
2. Group them under **New**, **Improved** and **Fixed**. Skip chore, test and refactor commits.
3. Write one plain-language line per item, focused on what the user can now do.
4. End with the version number and today's date.
