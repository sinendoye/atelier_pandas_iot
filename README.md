# Atelier Pandas — Nettoyage et analyse de données de capteurs IoT
## Contexte

Une entreprise possède plusieurs bâtiments équipés de capteurs IoT, collectant température, humidité, pression, consommation énergétique, état du capteur, bâtiment, date et heure de mesure. Cet atelier vise à importer, nettoyer et analyser ces données à l'aide de Pandas, avant leur transmission à un futur système de Machine Learning permettant de détecter des situations anormales.

## Objectifs pédagogiques
Manipuler les structures Series et DataFrame
Explorer, sélectionner et filtrer des données tabulaires
Créer, modifier et supprimer des colonnes
Trier et regrouper des données (groupby)
Détecter et traiter les valeurs manquantes et les doublons
Calculer des statistiques descriptives
Exporter des données nettoyées (CSV, JSON)

## Structure du projet
atelier_pandas_iot/
│
├── data/
│   └── mesures_capteurs.csv         # jeu de données brut fourni
│
├── notebooks/
│   └── atelier_pandas_iot.ipynb     # notebook contenant l'ensemble de l'atelier
│
└── exports/
    ├── donnees_nettoyees.csv        # export final, données nettoyées
    └── donnees_nettoyees.json       # export final, format JSON

## Contenu de l'atelier
**Partie	Sujet**
1	Series (création, index, sélection)
2	DataFrame (création, import CSV)
3	Exploration (head, tail, info, describe)
4	Sélection (loc, iloc)
5	Manipulation des colonnes (ajout, renommage, suppression)
6	Filtrage conditionnel
7	Tri (sort_values)
8	Analyse et agrégation (groupby)
9	Gestion des valeurs manquantes
10	Gestion des doublons
11	Statistiques descriptives
12	Exportation (CSV, JSON)
13	Bonus

## Environnement technique
Python 3
Pandas, NumPy
Jupyter Notebook (exécuté via VS Code, environnement virtuel dédié)
