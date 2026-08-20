# Global Sales Dashboard - Power BI

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](https://app.powerbi.com)

## 📊 Aperçu du Projet

Ce projet présente un tableau de bord interactif développé avec **Power BI** pour analyser les données de ventes globales de la boutique Superstore. Le dashboard permet d'explorer les performances commerciales à travers différentes dimensions (région, catégorie, segment client) et de dégager des insights stratégiques.

![Sales Dashboard](Sales%20Dashboard.png)

## 🎯 Objectifs du Projet

- Analyser les tendances des ventes globales
- Évaluer la performance par région et pays
- Identifier les catégories de produits les plus rentables
- Analyser les segments clients
- Fournir des indicateurs clés de performance (KPIs) interactifs

## ⚡ Technologies Utilisées

| Technologie | Utilisation |
| :--- | :--- |
| **Microsoft Power BI** | Création du dashboard, visualisations et rapports interactifs |
| **Power Query** | Nettoyage et transformation des données (ETL) |
| **DAX** | Calculs personnalisés et mesures avancées |
| **MS Excel** | Stockage et gestion des données sources |

## 📁 Structure du Projet
```
Sales-Dashboard-Using-Power-BI/
├── Global Sales Dashboard Project.pbix # Fichier principal Power BI
├── global_superstore_data.xlsx # Jeu de données source
├── Sales Dashboard.png # Capture d'écran du dashboard
└── README.md # Documentation du projet
```

## 📊 Jeu de Données

Le jeu de données `global_superstore_data.xlsx` provient de Kaggle et contient les informations suivantes :

| Champ | Description |
| :--- | :--- |
| `Order ID` | Identifiant unique de la commande |
| `Order Date` | Date de la commande |
| `Ship Date` | Date d'expédition |
| `Ship Mode` | Mode d'expédition (Standard, Express, etc.) |
| `Customer ID` | Identifiant du client |
| `Customer Name` | Nom du client |
| `Segment` | Segment client (Consumer, Corporate, Home Office) |
| `City` | Ville du client |
| `State` | État/Province |
| `Country` | Pays |
| `Region` | Région géographique |
| `Product ID` | Identifiant du produit |
| `Category` | Catégorie de produit |
| `Sub-Category` | Sous-catégorie |
| `Product Name` | Nom du produit |
| `Sales` | Montant des ventes |
| `Quantity` | Quantité vendue |
| `Discount` | Taux de remise appliqué |
| `Profit` | Bénéfice réalisé |

**Source** : [Kaggle - Global Superstore 2016](https://www.kaggle.com/datasets/tahir1413/global-superstore-2016)

## 📈 Fonctionnalités du Dashboard

### 1. Vue d'Ensemble (Executive Summary)
- **KPIs principaux** : Total des ventes, bénéfices, quantités
- **Graphiques de tendances** : Évolution des ventes dans le temps
- **Filtres interactifs** : Par année, mois, région

### 2. Analyse par Région
- **Carte géographique** : Visualisation des ventes par pays
- **Performance régionale** : Comparaison des régions
- **Top pays** : Classement par chiffre d'affaires

### 3. Analyse des Produits
- **Performance par catégorie** : Ventes par catégorie de produit
- **Top produits** : Produits les plus vendus
- **Analyse des sous-catégories** : Détail par sous-catégorie

### 4. Analyse des Clients
- **Segmentation** : Répartition des ventes par segment
- **Top clients** : Clients les plus importants
- **Analyse comportementale** : Tendances d'achat

## 🚀 Comment Utiliser

### Option 1 : Accès direct via le fichier .pbix
1. Téléchargez le fichier `Global Sales Dashboard Project.pbix`
2. Ouvrez-le avec **Power BI Desktop**
3. Explorez les différentes pages du dashboard
4. Utilisez les filtres et slicers pour interagir avec les données

### Option 2 : Publication sur Power BI Service
1. Ouvrez le fichier .pbix dans Power BI Desktop
2. Cliquez sur **"Publier"**
3. Sélectionnez votre espace de travail
4. Partagez le lien avec vos collègues

## 🔍 Insights Clés

Le dashboard permet de répondre à des questions stratégiques telles que :
- Quelles sont les régions les plus performantes ?
- Quels produits génèrent le plus de bénéfices ?
- Quels segments clients sont les plus rentables ?
- Quelles sont les tendances saisonnières des ventes ?

## 📝 Processus de Développement

1. **Extraction (ETL)** : Importation des données depuis Excel
2. **Transformation** : Nettoyage et préparation des données avec Power Query
3. **Chargement** : Intégration dans le modèle de données Power BI
4. **Modélisation** : Création des relations entre les tables
5. **Calculs DAX** : Création des mesures personnalisées
6. **Visualisation** : Conception des pages du dashboard
7. **Publication** : Déploiement sur Power BI Service

## 📝 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

Copyright © 2026 Hicham ERRIHANI. Tous droits réservés.

## 👨‍💻 Réalisé par

**Hicham ERRIHANI**  
Business Intelligence Developer & Data Analyst

[![email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:errihanihicham1@gmail.com)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hicham-errihani-815755266)
[![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hicham-Errihani)

---

⭐ Si ce projet vous a été utile, n'hésitez pas à lui donner une étoile sur GitHub !
