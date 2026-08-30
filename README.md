# Aïkido ASPTT Dijon

Fork du projet répertoire git https://github.com/clecuret/acgsite.

## Déploiement

Le site est généré et publié automatiquement sur GitHub Pages à chaque push sur `master`
via le workflow `.github/workflows/deploy.yml` (build PHP/Twig puis publication de `output/`).

Prérequis côté dépôt : **Settings → Pages → Source = GitHub Actions**.

Le workflow peut aussi être lancé à la main depuis l'onglet Actions (`Run workflow`).
