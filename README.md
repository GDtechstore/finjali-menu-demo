# MomLife Planner 2026

Application PWA (Progressive Web App) pour accompagner les nouvelles mamans au quotidien.

## Fonctionnalités

- **Suivi bébé** : tétées, sommeil, couches
- **Carnet de croissance** : poids, taille, périmètre crânien
- **Calendrier & Planificateur hebdomadaire**
- **Journal & humeur**
- **Budget bébé**
- **Notes et checklists** (post-partum, bébé, admin, santé)
- **Mode hors-ligne** (Service Worker + Cache)
- **Mode sombre**
- **Bilingue** FR / EN

## Démo en ligne

Déployez facilement via **GitHub Pages** :
1. Forkez ou téléchargez ce repo
2. Allez dans `Settings > Pages`
3. Source : `Deploy from a branch` → `main` → `/ (root)`
4. Votre app est live !

## Installation sur mobile

Ouvrez le site dans Chrome/Safari → "Ajouter à l'écran d'accueil".
L'application s'installe comme une vraie app native.

## Stockage des données

Les données sont stockées dans `localStorage` de votre navigateur.  
Pensez à utiliser les boutons **Save / Load** pour exporter/importer vos données en JSON.

## Structure

```
.
├── index.html          # Application principale
├── manifest.json       # Manifest PWA
├── sw.js               # Service Worker (hors-ligne)
├── icons/              # Icônes PWA (72×72 à 512×512)
└── README.md
```

## Licence

MIT — Libre d'utilisation personnelle.
