# Prédiction du Rendement du Riz Pluvial à Madagascar par Apprentissage Automatique

## Benchmark de 14 Algorithmes de Régression

**Auteurs :** RAZAFINDRAJOA Tsitohaina Andriamparany · Ravonimanantsoa Ndaohialy Manda-Vy · Rakotomalala Mamy Alain

**Statut :** Soumis à IJEST — en attente de validation éditoriale

---

## Résumé
Benchmark de 14 algorithmes ML entraînés sur 3 803 observations parcellaires
(Lac Alaotra, 2006–2010). Le HistGradientBoostingRegressor s'est révélé
le plus performant (R² = 0.181 · RMSE = 821 kg/ha).

---

## Structure du projet
```
projet_riz_madagascar/
├── data/
│   ├── raw/          # Données brutes
│   └── processed/    # Données nettoyées
├── notebooks/        # Jupyter notebooks (01 → 10)
├── figures/          # Graphiques et visualisations
├── results/          # Résultats et tableaux
└── models/           # Modèles entraînés (.pkl)
```

## Notebooks
| Notebook | Description |
|----------|-------------|
| 01_data_cleaning | Nettoyage des données |
| 02_EDA | Analyse exploratoire |
| 03_feature_engineering | Ingénierie des variables |
| 04_baseline_models | Modèles de base |
| 05_tree_models | Modèles d'arbres |
| 06_advanced_models | Modèles avancés |
| 07_best_model_analysis | Analyse du meilleur modèle |
| 08_validation | Validation statistique |
| 09_figures_publication | Figures pour publication |
| 10_tables_publication | Tableaux pour publication |

## Mots-clés
`riz pluvial` `machine learning` `gradient boosting` `SHAP` `Optuna` 
`Lac Alaotra` `Madagascar` `agriculture de conservation`