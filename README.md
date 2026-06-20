# Malika Kaddouri Nador

A static Arabic/Darija landing page for Malika Kaddouri in Nador, with a little French and direct WhatsApp contact.

## Local preview

Open `index.html` in a browser, or serve the folder with any static server:

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

## GitHub Pages

This repo publishes the static site to GitHub Pages from the `main` branch root.

Custom domain:

```text
malikakadouri.xyz
```

After signing in to GitHub CLI, publish with:

```powershell
gh repo create malika-kaddouri-nador --public --source . --remote origin --push
```

If GitHub CLI is not installed, create a public empty repository named `malika-kaddouri-nador`
on GitHub, then run:

```powershell
git remote add origin https://github.com/oussamaelhajoui/malika-kaddouri-nador.git
git push -u origin main
```

Then open the repository settings and enable GitHub Pages with **GitHub Actions** as the source if it is not enabled automatically.
