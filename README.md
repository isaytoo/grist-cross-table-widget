# 🔀 Grist Cross-Table Explorer Widget

**Author / Auteur : Said Hamadou (HmD)**
**License / Licence : Apache-2.0**

---

## 🇫🇷 Français

Widget personnalisé Grist pour croiser et joindre plusieurs tables par une clé commune, filtrer les résultats et générer une table dans le document.

### Fonctionnalités

- **Sélection multi-tables** : choisissez 2 tables ou plus à croiser
- **Mapping de clé commune** : sélectionnez la colonne ID dans chaque table
- **Jointure INNER / LEFT** : correspondances uniquement ou tout de la 1ère table
- **Sélection de colonnes** : choisissez les colonnes à afficher
- **Filtres dynamiques** : égal, contient, supérieur, inférieur, vide, etc.
- **Tri interactif** : cliquez sur les en-têtes pour trier
- **Export CSV** : exportez le résultat croisé
- **Génération de table** : créez une nouvelle table Grist avec les données croisées
- **Rafraîchissement** : mettez à jour la table générée en un clic
- **Horodatage** : colonne "Derniere_MAJ" ajoutée automatiquement
- **Bilingue FR/EN** : interface en français et anglais

### Installation

1. Dans Grist, ajoutez un widget **Personnalisé**
2. URL : `https://isaytoo.github.io/grist-cross-table-widget/`
3. Niveau d'accès : **Accès complet au document**

### Structure

| Fichier | Description |
|---------|-------------|
| `index.html` | Interface utilisateur |
| `widget.js` | Logique du widget |
| `package.json` | Métadonnées du widget |
| `vercel.json` | Configuration de déploiement |
| `LICENSE` | Licence Apache-2.0 |

---

## 🇬🇧 English

Custom Grist widget to cross-reference and join multiple tables by a common key, filter results and generate a table in the document.

### Features

- **Multi-table selection**: choose 2 or more tables to cross-reference
- **Common key mapping**: select the ID column in each table
- **INNER / LEFT join**: matches only or all from 1st table
- **Column selection**: choose which columns to display
- **Dynamic filters**: equals, contains, greater than, less than, empty, etc.
- **Interactive sorting**: click headers to sort
- **CSV export**: export the cross-referenced result
- **Table generation**: create a new Grist table with the joined data
- **Refresh**: update the generated table in one click
- **Timestamp**: "Derniere_MAJ" column added automatically
- **Bilingual FR/EN**: French and English interface

### Installation

1. In Grist, add a **Custom** widget
2. URL: `https://isaytoo.github.io/grist-cross-table-widget/`
3. Access level: **Full document access**

### Structure

| File | Description |
|------|-------------|
| `index.html` | User interface |
| `widget.js` | Widget logic |
| `package.json` | Widget metadata |
| `vercel.json` | Deployment configuration |
| `LICENSE` | Apache-2.0 license |
