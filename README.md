# ProBeats — Maquettes & Wireframes Penpot

> Site e-commerce ProBeats — Marque de materiel audio haut de gamme

## Livrable

**Repository GitHub** : https://github.com/Pyrostars-ui/probreats-maquettes-penpot

**Projet Penpot** : Fichier `cef` (connecte via MCP Plugin) — **11 pages**

## Structure du projet Penpot (11 pages)

### Design System
| # | Page | Contenu |
|---|------|---------|
| 0 | 🎨 Design System | Palette (6 couleurs), Typographie (10 styles), Composants (Boutons, Card, Input), Grille & Espacements (8-80px), Icônes (10 pictogrammes) |

### Pages Desktop (1440px)
| # | Page | Type | Organisation calques |
|---|------|------|---------------------|
| 1 | Desktop - Accueil | Maquette | 01-Header, 02-Hero, 03-Produits, 04-Temoignages, 05-Footer |
| 2 | Desktop - Produit | Wireframe | 01-Header, 02-Bloc Produit, 03-Slogan, 04-Caracteristiques, 05-Footer |
| 3 | Desktop - Commande | Wireframe | 01-Header, 02-Recap, 03-Livraison, 04-Paiement, 05-Confirmer, 06-Footer |
| 4 | Desktop - A propos | Wireframe | 01-header, 02-hero-about, 03-section-histoire, 04-section-points-forts, 05-footer |
| 5 | Desktop - Assistance | Wireframe | 01-header, 02-section-services, 03-section-faq, 04-section-contact, 05-footer |

### Pages Mobile (375px)
| # | Page | Type | Organisation |
|---|------|------|-------------|
| 6 | Mobile - Accueil | Maquette | 01-header, 02-hero, 03-section-produits, 04-section-temoignages, 05-footer |
| 7 | Mobile - Produit | Wireframe | Header, Titre, Photo, Prix, CTA, Slogan, Caracs, Footer |
| 8 | Mobile - Commande | Wireframe | Header, Titre, Recap, Livraison, Paiement, Footer |
| 9 | Mobile - A propos | Wireframe | Header, Titre, Hero, Histoire, Points forts, Footer |
| 10 | Mobile - Assistance | Wireframe | Header, Titre, Services, FAQ, Contact, Footer |

## Design System — Contenu détaillé

### 01 — Palette de couleurs (6 swatches)
| Nom | Hex | Usage |
|-----|-----|-------|
| Noir Charbon | #292A2D | Texte, footer, titres |
| Teal Foncé | #009099 | Boutons primaires, prix |
| Turquoise | #41B4BB | Secondaire, hover |
| Turquoise Clair | #7EDCE1 | Fonds hero, badges |
| Taupe | #B6A299 | Texte secondaire |
| Blanc | #FFFFFF | Fonds, texte sur foncé |

### 02 — Typographie (10 styles — Barlow Condensed)
| Style | Taille | Poids | Usage |
|-------|--------|-------|-------|
| H1 | 48px | 700 | Titres hero |
| H2 | 36px | 700 | Titres section |
| H3 | 28px | 600 | Sous-titres, slogans |
| H4 | 22px | 600 | Titres cards |
| Corps | 16px | 400 | Texte courant |
| Corps Small | 14px | 400 | Texte secondaire |
| Bouton | 16px | 600 | Texte boutons |
| Prix | 24px | 700 | Prix produits |
| Caption | 12px | 400 | Mentions légales |
| Nav | 16px | 400 | Navigation |

### 03 — Composants
- **Bouton Primaire** : Fond #009099, texte blanc, radius 8px
- **Bouton Secondaire** : Fond blanc, bordure #009099
- **Bouton Disabled** : Fond #E0E0E0, texte #9E9E9E
- **Card Produit** : Image + Nom + Prix + CTA
- **Input** : Fond #F5F5F5, focus bordure #009099

### 04 — Grille & Espacements
- XS: 8px | SM: 16px | **MD: 24px (padding bloc)** | LG: 40px | XL: 80px
- Desktop: 1440px (marges 80px) | Mobile: 375px (marges 24px)

### 05 — Icônes (10 pictogrammes)
Panier, Utilisateur, Recherche, Menu, Favori, Livraison, Garantie, Support, Retour, Paiement

## Composants (Bibliothèque Penpot)
Header, Footer, Bouton Primaire, Bouton Secondaire, Card Produit

## Fichiers du repository

```
probreats-maquettes-penpot/
├── README.md                    ← Ce fichier
├── docs/
│   ├── STYLES.md                ← Guide des styles
│   ├── COMPOSANTS.md            ← Documentation des composants
│   ├── PAGES.md                 ← Description des 11 pages
│   └── PROTOTYPE.md             ← Flow utilisateur + 10 interactions
├── presentation/
│   └── index.html               ← Page de presentation client
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

## Client

**ProBeats** — Marque creee en 2020, materiel audio sans fil haut de gamme.
Cible : jeunes, mobiles, audiophiles.
Produits : Casque audio, Enceinte Bluetooth, Enceinte studio.

---
*Brief : Maquetter le site ProBeats avec Penpot — Desktop & Mobile + Design System*
