# Publish Commands (GitHub Pages)

Run these commands from terminal.

## 1) Create a clean folder for public legal repo

```bash
mkdir -p /tmp/little-noor-legal
cp -R /Users/brelamoon/Documents/Playground/legal/public-site/. /tmp/little-noor-legal/
cd /tmp/little-noor-legal
```

## 2) Init and push to public repo `little-noor`

```bash
git init
git add .
git commit -m "Legal pages for app store links"
gh repo create little-noor --public --source=. --remote=origin --push
```

## 3) Enable GitHub Pages

In GitHub:

- Repository `little-noor`
- Settings -> Pages
- Build and deployment: `Deploy from a branch`
- Branch: `main` / `(root)`

Then links will be:

- `https://brelamoon.github.io/little-noor/privacy-policy/`
- `https://brelamoon.github.io/little-noor/terms/`
