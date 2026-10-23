# Composants Réutilisables — ProBeats

Tous les composants sont disponibles dans la bibliothèque locale Penpot (Assets).

## 1. Header

**Nom** : `Header`
**Usage** : Toutes les pages (desktop + mobile)

### Desktop (1440x80px)
- Logo ProBeats (cercle + wordmark) — gauche
- Navigation : Produits, À propos, Assistance — centre
- Panier (0) — droite
- Bouton Connexion (fond `#009099`, texte blanc) — extrême droite
- Ligne de séparation basse (`#E0E0E0`, 1px)

### Mobile (375x64px)
- Logo ProBeats — gauche
- Menu burger + Panier — droite

## 2. Footer

**Nom** : `Footer`
**Usage** : Toutes les pages

### Desktop (1440x320px)
- Fond `#292A2D` (noir charbon)
- 4 colonnes de liens : Produits, À propos, Assistance, Légal
- Colonne Contact : email, téléphone
- Colonne Réseaux sociaux : 5 icônes circulaires (`#009099`)
- Newsletter : input email + bouton OK
- Copyright : `© 2026 ProBeats. Tous droits réservés.`

### Mobile (375x400px)
- Fond `#292A2D`
- 4 colonnes de liens en 2x2
- Contact + Réseaux sociaux côte à côte
- Copyright en bas

## 3. Bouton Primaire

**Nom** : `Bouton Primaire`
**Dimensions** : 200x48px (desktop), variable (mobile)

| Propriété | Valeur |
|-----------|--------|
| Fond | `#009099` (Teal Foncé) |
| Texte | `#FFFFFF` (Blanc), 16px, SemiBold |
| Border radius | 8px |
| Padding | 24px horizontal |

**États** : Default, Hover (fond `#41B4BB`), Active (fond `#007780`), Disabled (opacité 0.5)

## 4. Bouton Secondaire

**Nom** : `Bouton Secondaire`
**Dimensions** : 200x48px (desktop), variable (mobile)

| Propriété | Valeur |
|-----------|--------|
| Fond | `#FFFFFF` (Blanc) |
| Bordure | 2px `#009099` |
| Texte | `#009099`, 16px, SemiBold |
| Border radius | 8px |

## 5. Card Produit

**Nom** : `Card Produit`
**Dimensions** : 320x400px (desktop), 327x160px (mobile)

### Structure
1. **Image produit** — placeholder coloré (haut, 200px desktop / 100px mobile)
2. **Nom du produit** — 20-22px, Bold, `#292A2D`
3. **Description** — 14px, Regular, `#5A5A5A`
4. **Prix** — 20-24px, Bold, `#009099`
5. **Bouton "Ajouter au panier"** — pleine largeur, fond `#009099`

### Variantes
- **Desktop** : verticale, image en haut
- **Mobile** : horizontale, image à gauche (100px), contenu à droite

## Utilisation dans Penpot

1. Ouvrir le panel **Assets** (librairie locale)
2. Glisser-déposer le composant sur la page
3. Modifier le contenu (texte, couleurs) selon le contexte
4. Pour personnaliser : clic droit → **Detach** (détacher du composant)
