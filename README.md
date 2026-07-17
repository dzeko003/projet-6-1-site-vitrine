# 🦷 Sourire Plus — Cabinet Dentaire

Site vitrine statique pour le **Cabinet Dentaire Sourire Plus** à Brazzaville, Congo.

> **Démonstration :** [https://dzeko003.github.io/projet-6-1-site-vitrine/](https://dzeko003.github.io/projet-6-1-site-vitrine/)

---

## Aperçu

Site web responsive d'une page principale (accueil) avec deux pages internes (services et contact), conçu pour présenter le cabinet, ses soins, son équipe et permettre la prise de rendez-vous.

## Pages

| Page         | Fichier         | Contenu                                                                                                                                                                       |
| ------------ | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Accueil**  | `index.html`    | Hero, statistiques (15+ ans, 5000+ patients, etc.), 3 soins populaires, parcours patient, manifeste, équipe (3 praticiens), témoignages, galerie du cabinet, FAQ, coordonnées |
| **Services** | `services.html` | Détail des 6 soins : Consultation, Détartrage, Blanchiment, Orthodontie, Implants, Urgences — chaque soin avec durée et sous-points                                           |
| **Contact**  | `contact.html`  | Coordonnées, plan Google Maps, formulaire de contact (nom, téléphone, email, sujet, message), FAQ étendue                                                                     |

## Fonctionnalités

- Design moderne et épuré avec la police **Poppins** (titres) et **Inter** (corps)
- Palette de couleurs : bleu (`#2563eb`) sur fond clair
- Navigation fixe avec menu burger sur mobile
- Animations CSS au survol (cartes de soins, équipe, galerie, FAQ)
- Galerie d'images avec filtre monochrome au repos, couleur au survol
- FAQ en accordéon (`<details>` / `<summary>`)
- Formulaire de contact avec validation native
- Icônes **Font Awesome 7**
- Responsive (3 breakpoints : desktop, tablette `≤992px`, mobile `≤640px`)

## Structure du projet

```
.
├── index.html       # Page d'accueil
├── services.html    # Page des soins
├── contact.html     # Page de contact
├── style.css        # Feuille de style unique
└── README.md        # Ce fichier
```

## Ressources externes

- **Polices :** [Google Fonts](https://fonts.googleapis.com) — Poppins & Inter
- **Icônes :** [Font Awesome 7](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.3.0/css/all.min.css)
- **Images :** [Unsplash](https://unsplash.com) (photos d'illustration du cabinet et de l'équipe)
- **Carte :** Google Maps (iframe embed)

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucune build ni serveur nécessaire — le site est 100% statique.
