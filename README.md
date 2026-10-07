# Analyse Exploratoire des Données de Ventes

Ce projet réalise une analyse exploratoire approfondie (EDA) d'un jeu de données de ventes régionales, visant à évaluer la performance commerciale, la rentabilité par catégorie et la qualité des données.

##  Méthodes & Fonctions Pandas utilisées

- **Groupements & Agrégations :** `groupby()`, `agg()`, `sum()`, `mean()`, `max()`
- **Structure & Croisements :** `pivot_table()`, `aggfunc`, `reset_index()`, `loc[]`
- **Analyse des fréquences & Segmentations :** `value_counts()`, `pd.cut()`
- **Tri & Sélection des extrêmes :** `sort_values()`, `ascending`, `nlargest()`, `idxmax()`

## Résultats clés de l'analyse

- Identification des catégories les plus rentables par région (Kinshasa vs Lubumbashi).
- Évaluation du panier moyen et de la dispersion des revenus par transaction.
- Nettoyage et vérification de la qualité des données (détection d'outliers par IQR).
