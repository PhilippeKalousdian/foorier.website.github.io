# Foorier - Site Jekyll

Site web pour Foorier basé sur le thème Agency Jekyll.

## Structure des fichiers

```
foorier-jekyll/
├── _config.yml              # Configuration principale
├── _data/
│   ├── home.yml             # Contenu page d'accueil
│   ├── navigation.yml       # Menu de navigation
│   ├── clients.yml          # Page clients
│   ├── expertises.yml       # Page expertises
│   ├── solutions.yml        # Page solutions
│   └── contact.yml          # Page contact
├── _layouts/
│   ├── default.html         # Layout principal
│   ├── page.html            # Layout pages
│   └── post.html            # Layout articles
├── _posts/                  # Articles de blog
├── css/
│   └── foorier.css          # Styles personnalisés
├── img/                     # Images (à ajouter)
│   ├── logo.png
│   ├── header-bg.jpg
│   ├── mission.png
│   ├── offre-cout.png
│   ├── offre-economies.png
│   ├── offre-conformite.png
│   ├── intervention-diagnostic.png
│   ├── intervention-conception.png
│   ├── intervention-pilotage.png
│   ├── testimonial-bg.png
│   ├── clients-header.jpg
│   ├── newsletter-bg.png
│   ├── expertise-reglementation.png
│   ├── expertise-batiments.png
│   ├── expertise-cvc.png
│   ├── expertise-iot.png
│   ├── solutions-architecture.jpg
│   └── blog/
│       ├── report-bacs.png
│       ├── batiments-potemkine.png
│       ├── smartbuilding-babel.png
│       ├── smart-buildings-chiffres.jpg
│       ├── operat.png
│       ├── decret-bacs.png
│       └── decret-tertiaire.png
├── index.html               # Page d'accueil
├── clients.html             # Page clients
├── expertises.html          # Page expertises
├── solutions.html           # Page solutions
├── contact.html             # Page contact
├── blog.html                # Liste des articles
└── Gemfile                  # Dépendances Ruby
```

## Images à placer

Télécharge les images depuis foorier.fr et place-les dans le dossier `img/` :

### Logo
- `logo.png` - Logo Foorier

### Page d'accueil
- `header-bg.jpg` - Image hero (bureaux tertiaires)
- `mission.png` - Image section mission
- `offre-cout.png` - Icône coût d'investissement
- `offre-economies.png` - Icône économies d'énergie
- `offre-conformite.png` - Icône conformité
- `intervention-diagnostic.png` - Icône diagnostics
- `intervention-conception.png` - Icône conception
- `intervention-pilotage.png` - Icône pilotage
- `testimonial-bg.png` - Image témoignage

### Page clients
- `clients-header.jpg` - Image header clients
- `newsletter-bg.png` - Image newsletter

### Page expertises
- `expertise-reglementation.png`
- `expertise-batiments.png`
- `expertise-cvc.png`
- `expertise-iot.png`

### Page solutions
- `solutions-architecture.jpg` - Schéma architecture

### Blog (dans img/blog/)
- `report-bacs.png`
- `batiments-potemkine.png`
- `smartbuilding-babel.png`
- `smart-buildings-chiffres.jpg`
- `operat.png`
- `decret-bacs.png`
- `decret-tertiaire.png`

## Installation locale

```bash
bundle install
bundle exec jekyll serve
```

## Déploiement GitHub Pages

1. Push le repo sur GitHub
2. Dans Settings > Pages, sélectionne la branche `main`
3. Le site sera accessible sur `https://username.github.io/repo-name/`

## Configuration

### Formulaire de contact

Modifie `_data/contact.yml` pour configurer Formspree :
```yaml
form_action: "https://formspree.io/f/VOTRE_ID"
```

### Google Analytics

Dans `_config.yml` :
```yaml
google_analytics: UA-XXXXXXXX-X
```

### Couleurs

Les couleurs sont définies dans `css/foorier.css` :
```css
:root {
  --foorier-primary: #1a1a2e;
  --foorier-secondary: #16213e;
  --foorier-accent: #0f3460;
  --foorier-highlight: #e94560;
}
```

Ajuste ces valeurs pour matcher exactement les couleurs de foorier.fr.
