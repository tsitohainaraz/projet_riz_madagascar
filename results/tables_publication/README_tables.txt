TABLEAUX HAUTE QUALITÉ POUR PUBLICATION
======================================================================

Répertoire : ../results/tables_publication/

TABLEAUX GÉNÉRÉS (CSV + LaTeX + Markdown) :
  1. Table1_descriptives          — Statistiques descriptives
  2. Table2_model_performances    — Performances top 10 modèles
  3. Table3_validation_statistics — Bootstrap, Permutation, Wilcoxon
  4. Table4_feature_importance    — Top 15 features (+ SHAP si dispo)
  5. Table5_classification_report — Analyse par classe rendement

SPÉCIFICATIONS TECHNIQUES :
  - Format CSV    : import Excel/LibreOffice direct
  - Format LaTeX  : intégration manuscrit .tex (booktabs)
  - Format Markdown : preview GitHub, README

CONFORMITÉ :
  ✅ APA 7th Edition : colonnes alignées, décimales cohérentes
  ✅ LaTeX booktabs  : toprule, midrule, bottomrule
  ✅ Lisibilité      : nombres arrondis (4 décimales max)

UTILISATION LaTeX :
  \input{tables_publication/Table1_descriptives.tex}

======================================================================
