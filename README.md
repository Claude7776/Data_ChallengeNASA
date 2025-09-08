# Data_ChallengeNASA
ChallengeNASA2025

# 🌌 NASA Exoplanets Simplified Dataset

Bienvenue dans ce projet dédié à l'exploration des **exoplanètes** découvertes par la NASA ! 🚀  

Ce dépôt contient une version **simplifiée et prête à explorer** du dataset officiel du [NASA Exoplanet Archive](http://exoplanetarchive.ipac.caltech.edu).

---

## 📂 Contenu du dépôt

- `exoplanets_simplified.csv` : CSV avec les colonnes principales suivantes :
  - `pl_name` : Nom de la planète  
  - `hostname` : Nom de l'étoile hôte  
  - `disc_year` : Année de découverte  
  - `discoverymethod` : Méthode de découverte  
  - `pl_orbper` : Période orbitale (jours)  
  - `pl_rade` : Rayon de la planète (Rayons terrestres)  
  - `pl_bmasse` : Masse de la planète (Masse terrestres)  
  - `pl_eqt` : Température d'équilibre (K)  
  - `st_teff` : Température de l'étoile (K)  
  - `st_rad` : Rayon de l'étoile (Rayons solaires)  
  - `st_mass` : Masse de l'étoile (Masse solaires)  

- Scripts Bash utilisés pour **nettoyer et extraire** les données (optionnel).

---

## ⚡ Objectif

- Fournir un fichier CSV **propre et léger** pour une analyse rapide.  
- Permettre une exploration facile avec **Python**, **Excel**, **LibreOffice**, ou directement dans le terminal avec `csvkit`.

---

## 🚀 Exemple d'utilisation

### Dans le terminal

# Affiche le CSV sous forme de tableau lisible
csvlook exoplanets_simplified.csv

# Filtrer les exoplanètes découvertes après 2020
csvgrep -c disc_year -m "2020" exoplanets_simplified.csv
---

## 🌌 Dashboard Interactif

En plus du CSV, ce projet inclut un dashboard interactif pour explorer les exoplanètes de manière visuelle et intuitive.

Fonctionnalités

`Visualisation graphique des exoplanètes et de leurs étoiles

`Graphiques dynamiques et interactifs

`Filtrage et organisation des données par année, rayon, masse, etc.

## Technologies utilisées

`HTML / CSS / JavaScript

`Chart.js pour les graphiques

`Miller pour le traitement CSV/JSON
