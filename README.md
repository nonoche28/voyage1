# Déploiement GitHub Pages (rapide)

## Option A — Dépôt `username.github.io` (site principal)
1. Crée un dépôt **public** nommé **`<ton-username>.github.io`**.
2. Ajoute `index.html` (et le dossier `data/` si tu veux charger `data/voyages.csv` automatiquement).
3. Valide sur la branche **`main`**. GitHub Pages sert automatiquement ton site à l’adresse : `https://<ton-username>.github.io/`.

## Option B — Dépôt projet (URL du type `/mon-site/`)
1. Crée un dépôt **public** (ex. `voyages-site`), branche **`main`**.
2. Ajoute les fichiers. Va dans **Settings → Pages → Deploy from a branch** et choisis **`main / root`**.
3. L’URL sera : `https://<ton-username>.github.io/voyages-site/`.

### CSV
- CSV principal attendu : `title;country;continent;days;budget_eur;season;themes;summary;map_url;cover_image_url`
- Pour auto-charger, place un fichier **`data/voyages.csv`** dans le dépôt. Sinon, utilise le bouton **Importer mon CSV** sur la page.

> Astuce : ajoute un fichier `.nojekyll` pour désactiver Jekyll si tu utilises des dossiers avec underscores.