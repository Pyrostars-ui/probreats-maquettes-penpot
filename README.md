# ProBeats — Maquettes & Wireframes Penpot

> Site e-commerce ProBeats — Marque de materiel audio haut de gamme (casques, enceintes Bluetooth, enceintes studio)

## Mission

Maquetter le site e-commerce de **ProBeats** dans **Penpot** (desktop + mobile) pour validation client avant developpement.

## Livrables

| Element | Description |
|---------|-------------|
| **10 pages Penpot** | 5 pages Desktop + 5 pages Mobile |
| **Maquette** | Page d'accueil (haute fidelite) |
| **Wireframes** | Produit, Commande, A propos, Assistance |
| **Composants** | Header, Footer, Boutons, Card Produit |
| **Styles** | 6 couleurs + 10 typographies (Barlow) |
| **Prototype** | Flow utilisateur interactif |

## Structure des pages

### Desktop (1440px)

| Page | Type | Contenu |
|------|------|---------|
| Desktop - Accueil | **Maquette** | Hero pleine page (casque phare), 3 cards produits, temoignages, newsletter |
| Desktop - Produit | Wireframe | Bloc produit (photo/prix/CTA), slogan + image ambiance, 3 caracteristiques |
| Desktop - Commande | Wireframe | Recapitulatif panier, formulaire livraison, paiement, confirmation |
| Desktop - A propos | Wireframe | Hero equipe, histoire marque (fondee 2020), timeline, 4 points forts |
| Desktop - Assistance | Wireframe | 4 services, FAQ (6 questions), contact rapide |

### Mobile (375px)

| Page | Type | Adaptation |
|------|------|------------|
| Mobile - Accueil | **Maquette** | Hero stack, produits en liste verticale, temoignage carrousel |
| Mobile - Produit | Wireframe | Photo full-width, prix, CTA sticky, caracteristiques en liste |
| Mobile - Commande | Wireframe | Recap + livraison + paiement en sections empilees |
| Mobile - A propos | Wireframe | Timeline verticale, points forts en grille 2x2 |
| Mobile - Assistance | Wireframe | Services 2x2, FAQ accordeon, CTA contact |

## Identite graphique

### Police
**Barlow Condensed** (disponible nativement dans Penpot)
- Poids : 200 (Thin), 300 (Light), 400 (Regular), 600 (SemiBold), 700 (Bold), 900 (Black)

### Palette de couleurs

| Nom | Hex | Usage |
|-----|-----|-------|
| PB Noir Charbon | `#292A2D` | Texte principal, footer, titres |
| PB Teal Foncé | `#009099` | Boutons primaires, prix, accents |
| PB Turquoise | `#41B4BB` | Elements secondaires, hover |
| PB Turquoise Clair | `#7EDCE1` | Fonds hero, surlignages |
| PB Taupe | `#B6A299` | Texte secondaire, bordures |
| PB Blanc | `#FFFFFF` | Fonds, texte sur fonce |

### Logo
- **PROBEATS** — Cercle + wordmark (recree en vectoriel dans Penpot)

## Grille & espacements

- **Padding blocs de contenu** : 24px
- **Desktop** : conteneur 1440px, marges laterales 80px
- **Mobile** : conteneur 375px, marges laterales 24px
- **Border radius** : 4px (petits), 6px (boutons), 8px (cards), 12px (grandes cards), 18px (badges)

## Prototype — Flow utilisateur

```
Accueil --> Produit --> Commande --> Confirmation
   |
   +--> A propos
   |
   +--> Assistance --> Contact
```

**Interactions cles :**
1. Nav "Produits" -> Page Produit
2. Nav "A propos" -> Page A propos
3. Nav "Assistance" -> Page Assistance
4. Hero "Decouvrir le casque" -> Page Produit
5. Card "Voir le produit" -> Page Produit
6. Produit "Ajouter au panier" -> Page Commande
7. Logo -> Retour Accueil (toutes pages)
8. Footer liens -> Pages correspondantes

## Fichiers

```
probreats-maquettes-penpot/
├── README.md              <- Ce fichier
├── docs/
│   ├── STYLES.md          <- Guide des styles (couleurs, typo, espacements)
│   ├── COMPOSANTS.md      <- Documentation des composants reutilisables
│   ├── PAGES.md           <- Description detaillee de chaque page
│   └── PROTOTYPE.md       <- Flow utilisateur et interactions
├── penpot/
│   └── README.md          <- Instructions d'acces au projet Penpot
└── exports/               <- Exports PNG/SVG (a generer depuis Penpot)
```

## Acces au projet Penpot

Le projet est disponible dans Penpot sous le nom **"cef"** (fichier connecte au MCP).

Pour y acceder :
1. Ouvrir Penpot (app ou web)
2. Le fichier contient 10 pages organisees Desktop / Mobile
3. Les composants sont dans la bibliotheque locale (Assets)
4. Les styles (couleurs + typographies) sont dans les librairies

## Client

**ProBeats** — Marque creee en 2020, materiel audio sans fil haut de gamme.
Cible : jeunes, mobiles, audiophiles.
Produits phares : Casque audio, Enceinte Bluetooth, Enceinte studio.

---

*Projet realise dans le cadre du brief "Maquetter le site ProBeats" — Livraison : maquettes Penpot Desktop & Mobile.*
