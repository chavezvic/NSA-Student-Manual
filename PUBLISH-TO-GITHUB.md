# Publish to GitHub

## Option 1: GitHub website

1. Sign in to GitHub.
2. Create a new repository.
3. Name it `NSA-Student-Manual`.
4. Do not initialize it with a README because this package already contains one.
5. Upload the repository files.
6. Commit the files.

## Option 2: GitHub CLI

Install and authenticate GitHub CLI, then run from the folder containing this repository:

```bash
gh auth login
gh repo create NSA-Student-Manual --public --source=. --remote=origin --push
```

## Option 3: Git command line

Create an empty repository on GitHub, then run:

```bash
git init
git add .
git commit -m "Initial NSA student manual"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/NSA-Student-Manual.git
git push -u origin main
```

Replace `<YOUR-USERNAME>` with your GitHub username.
