# Hermes Pages — Test Deployment

Simple static site published via [GitHub Pages](https://pages.github.com/) from the `main` branch.

## 🔗 Live Site
**https://gennadiyd.github.io/hermes-pages/**

## 📦 Deployment
- **Source:** `main` branch, root folder (`/`)
- **Pushed by:** Hermes Agent (Docker container)
- **SSH key:** `github_hermes_pages` (ed25519)

## 🛠 Local Development
```bash
git clone git@github.com:GennadiyD/hermes-pages.git
cd hermes-pages
# Edit index.html
git add -A && git commit -m "Update" && git push
```

## 📄 License
MIT — feel free to use as a template.