# Nina Carducci — Portfolio Photographe

Site vitrine d'une photographe professionnelle basée en Île-de-France. Projet réalisé dans le cadre du parcours Développeur Web d'OpenClassrooms (Projet 4).

## Structure du projet

```
Nina-Carducci-Dev-master/
├── index.html
└── assets/
    ├── bootstrap/          # Bootstrap 5 (CSS + JS)
    ├── images/
    │   ├── gallery/        # Photos de la galerie (concerts, entreprises, mariages, portraits)
    │   └── slider/         # Photos du carrousel
    ├── maugallery.js       # Plugin jQuery pour la galerie filtrée
    ├── scripts.js          # Initialisation de la galerie
    └── style.css           # Styles personnalisés
```

## Technologies

- HTML5 / CSS3
- [Bootstrap 5](https://getbootstrap.com/) — mise en page et carrousel
- [jQuery 3.4.1](https://jquery.com/) — manipulation du DOM
- [mauGallery](https://github.com/xSAVIKx/mauGallery) — galerie filtrée avec lightbox
- Google Fonts : Inter, Spectral

## Fonctionnalités

- **Navigation** sticky avec liens d'ancrage et lien Instagram
- **Carrousel** plein écran avec trois photos (Bootstrap)
- **Galerie** filtrée par catégorie (Concert, Entreprises, Mariages, Portrait) avec lightbox et navigation entre photos
- **Section services** avec tarifs (Shooting, Retouches, Album)
- **Formulaire de contact**
- **Design responsive** (breakpoints à 1180px, 1000px et 650px)

## Lancer le projet

Ouvrir `index.html` directement dans un navigateur, ou servir le dossier avec un serveur local :

```bash
npx serve .
# ou
python3 -m http.server
```
