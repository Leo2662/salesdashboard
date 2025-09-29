# Dashboard Prospection

Ce projet est un tableau de bord simple pour suivre le nombre de RDV de prospection semaine par semaine.

## Déploiement sur GitHub Pages

1. Crée un nouveau dépôt GitHub (ex: `prospection-dashboard`).
2. Ajoute les fichiers `index.html` et `data.csv` à la racine du dépôt.
3. Active GitHub Pages :
   - Va dans les **Settings** du dépôt.
   - Section **Pages** → Source : sélectionne la branche `main` et le dossier `/root`.
4. Ton dashboard sera accessible à l'adresse :  
   `https://tonpseudo.github.io/prospection-dashboard/`

## Mise à jour des données

Pour ajouter une nouvelle semaine :
- Modifie le fichier `data.csv` dans GitHub.
- Commits → le dashboard se met à jour automatiquement.

## Technologies utilisées

- [Chart.js](https://www.chartjs.org/) pour les graphiques.
- `fetch()` pour charger les données CSV dynamiquement.
