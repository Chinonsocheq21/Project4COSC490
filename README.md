# project4cosc490

Team project for **COSC 490 — Capstone**, Morgan State University, Fall 2026.

## Getting started

```bash
git clone https://github.com/Chinonsocheq21/project4cosc490.git
cd project4cosc490
```

## How we work

We never commit straight to `main`. `main` is protected and always has to build.

1. Pull the latest `main`:
   ```bash
   git checkout main
   git pull
   ```
2. Branch for your piece of work. Name it `yourname/what-it-does`:
   ```bash
   git checkout -b ana/login-form
   ```
3. Commit as you go, small and often:
   ```bash
   git add .
   git commit -m "Add login form validation"
   ```
4. Push your branch:
   ```bash
   git push -u origin ana/login-form
   ```
5. Open a Pull Request on GitHub, `your-branch` → `main`. Describe what you changed
   and how to test it.
6. One teammate reviews and approves, then it gets merged. Delete the branch after.

If two people touch the same file you'll get a merge conflict. Don't panic and don't
force-push — pull `main` into your branch, fix the conflicted lines, commit, push again.

## Team

| Name | GitHub | Role |
|---|---|---|
| Chinonso Egeolu | @Chinonsocheq21 | |
| | | |
| | | |
| | | |

## Layout

```
/src      application code
/docs     write-ups, diagrams, the deliverables for Dr. Mack
/assets   images, data, anything not code
```
