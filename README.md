# Malika Kaddouri Nador

A static Arabic/Darija landing page for Malika Kaddouri in Nador, with a little French and direct WhatsApp contact.

## Local preview

Open `index.html` in a browser, or serve the folder with any static server:

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

## GitHub Pages

This repo includes a GitHub Actions workflow that publishes the static site to GitHub Pages from `main`.

After signing in to GitHub CLI, publish with:

```powershell
gh repo create malika-kaddouri-nador --public --source . --remote origin --push
```

Then open the repository settings and enable GitHub Pages with **GitHub Actions** as the source if it is not enabled automatically.
