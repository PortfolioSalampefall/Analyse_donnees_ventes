📌 Présentation du projet

Ce projet consiste à réaliser une analyse complète des données de ventes afin d'identifier les tendances commerciales, d'évaluer la performance des produits et des régions et de dégager des indicateurs utiles à la prise de décision.

L'analyse combine Python pour l'Exploratory Data Analysis (EDA) et Power BI pour la visualisation et le reporting décisionnel.

🎯 Objectifs

Les principaux objectifs de ce projet sont :

Analyser l'évolution du chiffre d'affaires et du profit.
Identifier les produits et catégories les plus performants.
Analyser les ventes par région et zone géographique.
Étudier l'impact des remises sur les performances commerciales.
Analyser les coûts de livraison.
Identifier les tendances et anomalies dans les données.
Construire un dashboard interactif permettant le suivi des KPI commerciaux.
Transformer les données brutes en informations utiles à la prise de décision.
🗂️ Données

Le dataset contient notamment des informations relatives à :

Commandes
Produits
Catégories
Sous-catégories
Clients
Régions
Pays
Ventes
Remises
Profits
Coûts de livraison
Dates de commande et de livraison
🔄 Méthodologie
1. Collecte et préparation des données

Les données ont été importées puis analysées afin d'identifier :

Les valeurs manquantes
Les doublons
Les erreurs de format
Les types de données incorrects
Les valeurs aberrantes
Les incohérences dans les variables numériques et catégorielles
2. Nettoyage des données

Les principales opérations réalisées comprennent :

Nettoyage des colonnes
Conversion des types de données
Traitement des valeurs manquantes
Suppression des doublons
Vérification des valeurs aberrantes
Standardisation des variables
Préparation des données pour l'analyse
3. Analyse exploratoire — Python

Une Exploratory Data Analysis (EDA) a été réalisée avec Python afin d'examiner la structure et les principales tendances du dataset.

Analyses réalisées :

Statistiques descriptives
Analyse des distributions
Analyse des ventes
Analyse du profit
Analyse des catégories
Analyse géographique
Analyse des remises
Analyse des coûts de livraison
Analyse des corrélations entre variables numériques
4. Business Intelligence — Power BI

Les données préparées ont ensuite été exploitées dans Power BI afin de construire un reporting interactif.

Le modèle Power BI permet d'explorer les performances commerciales selon plusieurs dimensions :

Temps
Produit
Catégorie
Région
Pays
Client
📈 KPI principaux

Le dashboard permet notamment de suivre :

💰 Chiffre d'affaires
📈 Profit
📦 Nombre de commandes
🛒 Quantité vendue
💸 Remise moyenne
🚚 Coût de livraison
📊 Marge / taux de profit
📊 Visualisations

Le reporting comprend notamment :

Cartes KPI
Graphiques d'évolution temporelle
Bar charts
Donut charts
Treemaps
Tableaux et matrices
Analyse géographique
Filtres interactifs
Segmentation par catégorie et région
🔎 Principales analyses
Analyse temporelle

Analyse de l'évolution des ventes et du profit au cours du temps afin d'identifier :

Les périodes de forte activité
Les périodes de baisse
Les tendances saisonnières
Analyse des produits

Identification :

Des produits les plus vendus
Des produits générant le plus de chiffre d'affaires
Des produits les plus rentables
Des produits présentant une faible rentabilité
Analyse géographique

Analyse des performances commerciales par :

Pays
Région
Zone géographique

Une carte interactive permet de visualiser la répartition géographique des ventes.

Analyse des remises

Étude de la relation entre :

Discount → Sales → Profit

afin d'identifier l'impact des remises sur la rentabilité.

🛠️ Technologies utilisées
Technologie	Utilisation
🐍 Python	Analyse exploratoire
🐼 Pandas	Manipulation des données
📊 Matplotlib	Visualisation
📈 Plotly	Visualisations interactives
⚡ Power BI	Reporting et dashboard
🔢 DAX	Calcul des KPI
🔄 Power Query	Transformation des données
📗 Excel	Source et préparation des données
🔧 Git / GitHub	Versionnement du projet
📁 Structure du projet
Sales_Analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── sales_data_cleaned.ipynb
    └── sales_data_analysis.ipynb
│
├── powerbi/
│   └── sales_data_analysis.pbix    dashboard
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
💡 Compétences démontrées

Ce projet démontre des compétences en :

Data Cleaning
Exploratory Data Analysis
Business Intelligence
Data Visualization
KPI Development
DAX
Power Query
Power BI
Python
Pandas
Analyse commerciale
Data Storytelling
Git & GitHub
🚀 Perspectives d'amélioration

Les prochaines étapes pourraient inclure :

Création d'un modèle prédictif des ventes.
Prévision du chiffre d'affaires.
Segmentation des clients.
Détection automatique des anomalies.
Analyse de la Customer Lifetime Value.
Mise en place d'un pipeline ETL automatisé.
Automatisation de la mise à jour du dashboard.
👤 Auteur

Sallah DIA
Data Analyst | BI Analyst | Power BI Specialist

Compétences principales : Power BI · SQL · Python · Data Analysis · DAX · Power Query · IA

⭐
Ce projet fait partie de mon portfolio Data Analyst.
