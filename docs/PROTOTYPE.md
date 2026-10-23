# Prototype — Flow Utilisateur ProBeats

## Vue d'ensemble

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   ACCUEIL   │────▶│   PRODUIT   │────▶│   COMMANDE  │────▶│CONFIRMATION │
│  (Maquette) │     │ (Wireframe) │     │ (Wireframe) │     │  (à créer)  │
└──────┬──────┘     └─────────────┘     └─────────────┘     └─────────────┘
       │
       ├──────────▶┌─────────────┐
       │           │  À PROPOS   │
       │           │ (Wireframe) │
       │           └─────────────┘
       │
       └──────────▶┌─────────────┐
                   │  ASSISTANCE │
                   │ (Wireframe) │
                   └──────┬──────┘
                          │
                          ▼
                   ┌─────────────┐
                   │   CONTACT   │
                   │  (formulaire)│
                   └─────────────┘
```

## Interactions détaillées

### Navigation principale (Header)

| Élément | Action | Destination |
|---------|--------|-------------|
| Logo ProBeats | Click | Accueil (toutes les pages) |
| Nav "Produits" | Click | Page Produit |
| Nav "À propos" | Click | Page À propos |
| Nav "Assistance" | Click | Page Assistance |
| Panier (0) | Click | Page Commande |
| Bouton "Connexion" | Click | Modal/Overlay Connexion (à créer) |

### Page Accueil

| Élément | Action | Destination |
|---------|--------|-------------|
| Hero "Découvrir le casque" | Click | Page Produit |
| Card "Voir le produit" (x3) | Click | Page Produit (avec produit sélectionné) |
| Newsletter "OK" | Click | Toast confirmation (à créer) |
| Footer liens | Click | Pages correspondantes |
| Footer RS | Click | Liens externes (nouvel onglet) |

### Page Produit

| Élément | Action | Destination |
|---------|--------|-------------|
| "Ajouter au panier" | Click | Page Commande (panier mis à jour) |
| "En savoir plus" | Click | Scroll vers caractéristiques |

### Page Commande

| Élément | Action | Destination |
|---------|--------|-------------|
| "Confirmer la commande" | Click | Page Confirmation (à créer) |
| Retour panier | Click | Page Produit / Accueil |

### Page Assistance

| Élément | Action | Destination |
|---------|--------|-------------|
| FAQ item "+" | Click | Expand/Collapse réponse |
| "Nous contacter" | Click | Formulaire contact / Modal |

## Versions

| Version | Pages | Statut |
|---------|-------|--------|
| Desktop | 5 pages | Créées dans Penpot |
| Mobile | 5 pages | Créées dans Penpot |
| Prototype interactif | Flows | Documenté (à configurer dans Penpot) |

## Configuration dans Penpot

Pour activer le prototype interactif dans Penpot :

1. Sélectionner un élément (bouton, lien)
2. Panel **Interactions** (à droite)
3. **+ Add interaction**
4. Trigger : `On click` / `On tap`
5. Action : `Navigate to` → sélectionner la page cible
6. Animation : `Smart animate` (recommandé) ou `Instant`

### Flows à configurer

| # | Source | Trigger | Destination | Animation |
|---|--------|---------|-------------|-----------|
| 1 | Nav "Produits" (toutes pages) | On click | Desktop/Mobile - Produit | Smart animate |
| 2 | Nav "À propos" (toutes pages) | On click | Desktop/Mobile - À propos | Smart animate |
| 3 | Nav "Assistance" (toutes pages) | On click | Desktop/Mobile - Assistance | Smart animate |
| 4 | Logo (toutes pages) | On click | Desktop/Mobile - Accueil | Smart animate |
| 5 | Hero CTA (Accueil) | On click | Produit | Smart animate |
| 6 | Card "Voir le produit" (Accueil) | On click | Produit | Smart animate |
| 7 | "Ajouter au panier" (Produit) | On click | Commande | Smart animate |
| 8 | "Confirmer" (Commande) | On click | Confirmation (à créer) | Smart animate |
| 9 | FAQ "+" (Assistance) | On click | Expand (overlay) | Instant |
| 10 | Panier (Header) | On click | Commande | Smart animate |

## Parcours utilisateur type

### Parcours 1 : Achat rapide
```
Accueil → Hero CTA → Produit → Ajouter au panier → Commande → Confirmer → Confirmation
```

### Parcours 2 : Découverte
```
Accueil → Nav "À propos" → À propos → Nav "Produits" → Produit → Accueil
```

### Parcours 3 : Support
```
Accueil → Nav "Assistance" → FAQ → Contact → Formulaire
```

### Parcours 4 : Mobile
```
Accueil mobile → Menu burger → Produits → Produit → Panier → Commande
```
