---
name: commit-message
description: Writes a commit message in our team's Conventional Commits style. Use when the user asks for a commit message or is about to commit staged changes.
---

# Team commit message

1. Run `git diff --staged` and read the change.
2. Pick one type: feat, fix, refactor, docs, test, chore.
3. Write the subject as `type(scope): summary` in the imperative mood, max 72 characters.
4. Add a short body explaining *why* the change was made, wrapped at 72 characters.
5. If a ticket ID appears in the branch name (e.g. `SK-123`), add `Refs: SK-123` as the last line.
