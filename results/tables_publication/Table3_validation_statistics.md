| Test                                | Valeur   | IC95 inf   | IC95 sup   | p-value   |
|:------------------------------------|:---------|:-----------|:-----------|:----------|
| Bootstrap R² (B=1000)               | 0.1802   | 0.1337     | 0.2241     | —         |
| Bootstrap RMSE (B=1000)             | 821.0148 | 778.1482   | 866.5432   | —         |
| Bootstrap MAE (B=1000)              | 642.2143 | 605.8898   | 680.0971   | —         |
| Permutation (R²)                    | 0.1655   | —          | —          | 0.0099    |
| Wilcoxon vs LinearSVR (Optuna)      | —        | —          | —          | 0.0       |
| Wilcoxon vs SGD (Optuna)            | —        | —          | —          | 0.0       |
| Wilcoxon vs Ridge                   | —        | —          | —          | 0.0       |
| Wilcoxon vs ElasticNet              | —        | —          | —          | 0.0       |
| Wilcoxon vs Linear                  | —        | —          | —          | 0.0       |
| Wilcoxon vs Lasso                   | —        | —          | —          | 0.0       |
| Wilcoxon vs KNN (Optuna)            | —        | —          | —          | 0.0003    |
| Wilcoxon vs AdaBoost                | —        | —          | —          | 0.0006    |
| Wilcoxon vs LightGBM (opt)          | —        | —          | —          | 0.0025    |
| Wilcoxon vs Random Forest (opt)     | —        | —          | —          | 0.011     |
| Wilcoxon vs Decision Tree (opt)     | —        | —          | —          | 0.0119    |
| Wilcoxon vs CatBoost (opt)          | —        | —          | —          | 0.2015    |
| Wilcoxon vs Gradient Boosting (opt) | —        | —          | —          | 0.2377    |