---
date: 2026-05-07
slug: tabpfn-tabular-foundation-model
title: "TabPFN trending: foundation model for tabular data now handles 50K rows"
category: ml-engineering
source_name: "GitHub"
source_url: "https://github.com/PriorLabs/TabPFN"
tags: [tabular-data, foundation-model, sklearn, python, machine-learning]
top_story: false
---

TabPFN (Tabular Prior-data Fitted Network) is trending on GitHub with 6,600 stars and 218 new stars today. The latest version — TabPFN-2.5 — extends support to datasets with up to 50,000 rows and 2,000 features, a 20-fold increase in data cells compared to the previous version. On benchmarks up to this scale it outperforms manually tuned ensembles of XGBoost, LightGBM, and CatBoost, while requiring no hyperparameter search.

The practical upshot for a working data scientist: drop in your structured dataset, call fit/predict, and get strong out-of-the-box performance without the usual grid search. TabPFN handles missing values, categorical features, and outliers automatically. It works as a scikit-learn compatible estimator, so it slots into existing pipelines without refactoring. The model is built by PriorLabs and published with a Nature paper backing the original approach.

TabPFN is particularly useful for medium-scale structured data problems where you want a reliable baseline quickly — think internal business datasets, fraud detection, churn prediction — rather than large-scale production training runs. It will not replace specialized deep learning for very large tabular datasets, but for the common case of under-50K rows it is arguably the new default starting point.

Read more at [GitHub](https://github.com/PriorLabs/TabPFN).
