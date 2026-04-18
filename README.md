# Landing_page

Ce dépôt est prêt pour un déploiement via **GitHub Pages** avec le workflow :
`/.github/workflows/static.yml`.

## Publication sur GitHub Pages

1. Va dans **Settings > Pages** du dépôt.
2. Dans **Source**, choisis **GitHub Actions**.
3. Vérifie que la branche principale est `main` (le workflow se lance sur push vers `main`).
4. Push tes changements : le workflow **Deploy static content to Pages** publiera le site.
5. L’URL publiée sera disponible dans l’onglet **Actions** puis dans **Settings > Pages**.

## Point d’entrée du site

Le fichier d’entrée est `index.html` (racine nécessaire pour GitHub Pages).
