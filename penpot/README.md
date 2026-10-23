# Projet Penpot — ProBeats

## Informations du fichier

| Propriété | Valeur |
|-----------|--------|
| **Nom du fichier** | `cef` |
| **Plateforme** | Penpot (MCP Plugin connecté) |
| **Nombre de pages** | 10 |
| **Composants** | 5 (Header, Footer, Bouton Primaire, Bouton Secondaire, Card Produit) |
| **Couleurs librairie** | 6 couleurs ProBeats + couleurs existantes |
| **Typographies librairie** | 10 typographies ProBeats + typographies existantes |

## Liste des pages

### Desktop
1. `Desktop - Accueil` — Maquette haute fidélité
2. `Desktop - Produit` — Wireframe
3. `Desktop - Commande` — Wireframe
4. `Desktop - À propos` — Wireframe
5. `Desktop - Assistance` — Wireframe

### Mobile
6. `Mobile - Accueil` — Maquette haute fidélité
7. `Mobile - Produit` — Wireframe
8. `Mobile - Commande` — Wireframe
9. `Mobile - À propos` — Wireframe
10. `Mobile - Assistance` — Wireframe

## Comment accéder au projet

### Option 1 : Via Penpot MCP (recommandé)
Le fichier est connecté au serveur MCP Penpot. Utiliser les outils MCP pour interagir.

### Option 2 : Export Penpot
1. Dans Penpot, ouvrir le fichier `cef`
2. Menu **File** → **Export** (ou raccourci)
3. Formats disponibles : `.penpot` (natif), PNG, SVG, PDF

### Option 3 : Duplication
1. Ouvrir le fichier dans Penpot
2. **File** → **Duplicate** pour créer une copie

## Structure du fichier

```
cef/
├── Pages
│   ├── Desktop - Accueil (maquette)
│   ├── Desktop - Produit (wireframe)
│   ├── Desktop - Commande (wireframe)
│   ├── Desktop - À propos (wireframe)
│   ├── Desktop - Assistance (wireframe)
│   ├── Mobile - Accueil (maquette)
│   ├── Mobile - Produit (wireframe)
│   ├── Mobile - Commande (wireframe)
│   ├── Mobile - À propos (wireframe)
│   └── Mobile - Assistance (wireframe)
│
├── Assets (Bibliothèque locale)
│   ├── Composants : Header, Footer, Bouton Primaire, Bouton Secondaire, Card Produit
│   ├── Couleurs : PB Noir Charbon, PB Teal Foncé, PB Turquoise, PB Turquoise Clair, PB Taupe, PB Blanc
│   └── Typographies : PB H1-H4, PB Corps, PB Corps Small, PB Bouton, PB Prix, PB Caption, PB Nav
│
└── Prototype (à configurer)
    └── Interactions de navigation entre les pages
```

## Exports recommandés

Pour la présentation client, exporter :

| Page | Format | Usage |
|------|--------|-------|
| Desktop - Accueil | PNG (2x) | Présentation maquette |
| Mobile - Accueil | PNG (2x) | Présentation maquette responsive |
| Toutes les pages | PDF | Dossier de présentation complet |
| Toutes les pages | PNG (1x) | Documentation développeur |

### Paramètres d'export
- **Scale** : 1x (web) ou 2x (présentation HD)
- **Format** : PNG (fond transparent ou blanc)
- **Sélection** : Page entière ou sélection de boards
