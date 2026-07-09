# GitHub Pages Deployment Workflow

Ce projet montre comment déployer automatiquement un site statique vers GitHub Pages en utilisant GitHub Actions.

## Contenu du projet

- `index.html` : page web principale.
- `.github/workflows/deploy.yml` : workflow GitHub Actions qui déploie le site.
- `README.md` : documentation du projet.

## Fonctionnement

Le workflow se déclenche automatiquement lorsqu'une modification est effectuée sur le fichier `index.html` de la branche `main`.

Les étapes exécutées sont :

1. Récupération du dépôt.
2. Configuration de GitHub Pages.
3. Téléversement des fichiers du site.
4. Déploiement automatique vers GitHub Pages.

## URL du site

Une fois GitHub Pages activé, le site sera disponible à :

```
https://github.com/Chrystal-git/gh-deployment-workflow
```


## Technologies

- HTML5
- GitHub Actions
- GitHub Pages
