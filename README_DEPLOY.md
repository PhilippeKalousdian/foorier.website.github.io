# Migration Foorier

## Contenu créé

Ce dossier contient la configuration pour migrer Foorier.fr vers GitHub Pages.

## Déploiement

1. Copier tous les fichiers vers votre repository :
   ```bash
   cp -r foorier-content/* /chemin/vers/foorier.website.github.io/
   ```

2. Aller dans le repository :
   ```bash
   cd /chemin/vers/foorier.website.github.io/
   ```

3. Commit et push :
   ```bash
   git add .
   git commit -m "Migration contenu Foorier"
   git push origin main
   ```

4. Attendre 2-3 minutes et visiter :
   https://philippekalousdian.github.io/foorier.website.github.io/

## Images à ajouter

Placez les images dans :
- `assets/img/header-bg.jpg` (1920x1080)
- `assets/img/timeline/1.jpg`, `2.jpg`, `3.jpg`
- `assets/img/team/default.jpg`

Ou téléchargez depuis https://foorier.fr et placez-les dans les bons dossiers.
