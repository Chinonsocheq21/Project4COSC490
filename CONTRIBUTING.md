# Contributing

## The one rule
No commits directly to `main`. Everything arrives through a Pull Request that
somebody else approved.

## Branch names
`yourname/short-description` — e.g. `chinonso/db-schema`, `ana/login-form`.

## Commit messages
Present tense, says what it does: "Add user table migration", not "stuff" or "fixes".

## Pull requests
- Title says what it does.
- Body: what changed, why, and how to check it works.
- Tag one teammate as reviewer. Don't merge your own PR unless it's trivial and
  you've said so in the channel.
- Keep them small. A 40-file PR gets rubber-stamped, which is the same as no review.

## Before you push
- It runs.
- No secrets, keys, or `.env` files. If you commit one, tell the team immediately —
  deleting it in a later commit does NOT remove it from history.
- `git pull --rebase origin main` so your branch is on top of current `main`.

## When you hit a conflict
```bash
git checkout your-branch
git pull origin main
# fix the <<<<<<< sections by hand
git add .
git commit
git push
```
Never `git push --force` to a shared branch.
