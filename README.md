# ProBeats — Maquettes & Wireframes Penpot

> Site e-commerce ProBeats — Marque de materiel audio haut de gamme

## Livrable

**Repository GitHub** : https://github.com/Pyrostars-ui/probreats-maquettes-penpot

**Projet Penpot** : Fichier `cef` (connecte via MCP Plugin)

## Structure du projet Penpot

### Pages (10)

| # | Page | Type | Organisation calques |
|---|------|------|---------------------|
| 1 | Desktop - Accueil | Maquette | 01-Header, 02-Hero, 03-Produits, 04-Temoignages, 05-Footer |
| 2 | Desktop - Produit | Wireframe | 01-Header, 02-Bloc Produit, 03-Slogan, 04-Caracteristiques, 05-Footer |
| 3 | Desktop - Commande | Wireframe | 01-Header, 02-Recap, 03-Livraison, 04-Paiement, 05-Confirmer, 06-Footer |
| 4 | Desktop - A propos | Wireframe | 01-header, 02-hero-about, 03-section-histoire, 04-section-points-forts, 05-footer |
| 5 | Desktop - Assistance | Wireframe | 01-header, 02-section-services, 03-section-faq, 04-section-contact, 05-footer |
| 6 | Mobile - Accueil | Maquette | 01-header, 02-hero, 03-section-produits, 04-section-temoignages, 05-footer |
| 7 | Mobile - Produit | Wireframe | Header, Titre, Photo, Prix, CTA, Slogan, Caracs, Footer |
| 8 | Mobile - Commande | Wireframe | Header, Titre, Recap, Livraison, Paiement, Footer |
| 9 | Mobile - A propos | Wireframe | Header, Titre, Hero, Histoire, Points forts, Footer |
| 10 | Mobile - Assistance | Wireframe | Header, Titre, Services, FAQ, Contact, Footer |

### Composants (Bibliotheque Penpot)

| Composant | Description |
|-----------|-------------|
| Header | Logo + Nav (Produits, A propos, Assistance) + Panier + Connexion |
| Footer | 4-6 colonnes + Contact + Reseaux sociaux + Newsletter + Copyright |
| Bouton Primaire | Fond #009099, texte blanc, radius 8px |
| Bouton Secondaire | Fond blanc, bordure #009099, texte #009099 |
| Card Produit | Image + Nom + Prix + Bouton "Ajouter au panier" |

### Styles

| Categorie | Elements |
|-----------|----------|
| Couleurs (6) | PB Noir Charbon #292A2D, PB Teal Foncé #009099, PB Turquoise #41B4BB, PB Turquoise Clair #7EDCE1, PB Taupe #B6A299, PB Blanc #FFFFFF |
| Typographies (10) | PB H1 (48px), PB H2 (36px), PB H3 (28px), PB H4 (22px), PB Corps (16px), PB Corps Small (14px), PB Bouton (16px), PB Prix (24px), PB Caption (12px), PB Nav (16px) |
| Police | Barlow Condensed (poids: 200, 300, 400, 600, 700, 900) |

## Fichiers du repository

```
probreats-maquettes-penpot/
├── README.md                    ← Ce fichier
├── docs/
│   ├── STYLES.md                ← Guide des styles (couleurs, typo, espacements)
│   ├── COMPOSANTS.md            ← Documentation des composants
│   ├── PAGES.md                 ← Description detaillee des 10 pages
│   └── PROTOTYPE.md             ← Flow utilisateur + 10 interactions
├── presentation/
│   └── index.html               ← Page de presentation client (grille 10 pages)
├── penpot/
│   └── README.md                ← Acces au fichier Penpot
└── exports/
    └── README.md                ← Guide d'export PNG/SVG
```

## Prototype — Flow utilisateur

```
Accueil --> Produit --> Commande --> Confirmation
   |
   +--> A propos
   |
   +--> Assistance --> Contact
```

10 interactions documentees dans `docs/PROTOTYPE.md` (a configurer dans Penpot).

## Client

**ProBeats** — Marque creee en 2020, materiel audio sans fil haut de gamme.
Cible : jeunes, mobiles, audiophiles.
Produits : Casque audio, Enceinte Bluetooth, Enceinte studio.

---
*Brief : Maquetter le site ProBeats avec Penpot — Desktop & Mobile*
