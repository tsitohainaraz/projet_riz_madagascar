| Modèle                  |   R² (Test) |   RMSE (kg/ha) |   MAE (kg/ha) |
|:------------------------|------------:|---------------:|--------------:|
| HistGradientBoosting    |      0.1812 |        821.102 |       642.108 |
| CatBoost (opt)          |      0.1759 |        823.755 |       644.764 |
| Gradient Boosting (opt) |      0.1752 |        824.084 |       643.549 |
| Random Forest (opt)     |      0.1674 |        827.972 |       649.831 |
| LightGBM (opt)          |      0.1595 |        831.886 |       651.996 |
| AdaBoost                |      0.1355 |        843.727 |       661.905 |
| Decision Tree (opt)     |      0.1328 |        845.003 |       660.642 |
| SGD (Optuna)            |      0.106  |        857.999 |       676.991 |
| Linear                  |      0.1055 |        858.21  |       nan     |
| ElasticNet              |      0.1054 |        858.245 |       nan     |