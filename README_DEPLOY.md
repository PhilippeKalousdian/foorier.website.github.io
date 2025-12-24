# Site Foorier - Migration complète

## Contenu

Ce dossier contient la migration COMPLÈTE de https://foorier.fr vers GitHub Pages.

✅ Toutes les pages (Accueil, Clients, Expertises, Solutions, Contact)
✅ Tous les textes originaux
✅ Structure Jekyll configurée
✅ Navigation complète
✅ Couleurs et thème

## Déploiement

### Méthode 1 : Copie directe (recommandé)

```bash
# Copier tout vers votre repo
cp -r foorier-complete/* /chemin/vers/foorier.website.github.io/

# Ou sur Windows
xcopy /E /I foorier-complete\* C:\chemin\vers\foorier.website.github.io\
```

### Méthode 2 : Via VS Code

1. Glisser-déposer tous les fichiers de `foorier-complete/` vers `foorier.website.github.io/`
2. Écraser les fichiers existants si demandé

### Push vers GitHub

```bash
cd /chemin/vers/foorier.website.github.io/
git add .
git commit -m "Migration complète Foorier.fr"
git push origin main
```

## Images à ajouter

Téléchargez les images depuis foorier.fr et placez-les dans :

- `assets/img/header-bg.jpg` (image d'en-tête)
- `assets/img/timeline/1.jpg`, `2.jpg`, `3.jpg`
- `assets/img/team/1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`
- `assets/img/clients/1.jpg`, `2.jpg`, `3.jpg`

Ou utilisez temporairement des placeholders.

## Vérification

Après push, attendez 2-3 minutes puis visitez :
https://philippekalousdian.github.io/foorier.website.github.io/

## Support

Le thème utilisé : Agency Jekyll Theme
Documentation : https://github.com/raviriley/agency-jekyll-theme
