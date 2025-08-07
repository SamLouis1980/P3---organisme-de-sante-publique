#  Préparation des Données – Open Food Facts

##  Contexte

Dans le cadre d’un projet en collaboration avec **Santé Publique France**, notre mission était d’évaluer la faisabilité d’un système de **suggestion automatique** pour remplir les champs manquants de la base de données **Open Food Facts**.  
Ce projet vise à faciliter l’enrichissement de cette base de données open source, utilisée pour évaluer la qualité nutritionnelle des produits alimentaires.

Actuellement, la saisie manuelle des informations entraîne de nombreuses erreurs et des valeurs manquantes. Une meilleure qualité des données permettrait d’améliorer les analyses sanitaires, nutritionnelles, et les recommandations publiques.

---

##  Objectif

- Nettoyer et explorer en profondeur la base de données Open Food Facts.
- Identifier les variables les plus problématiques en termes de valeurs manquantes.
- Proposer des solutions automatisées de traitement des données (imputation, nettoyage, détection des valeurs aberrantes).
- Réaliser des visualisations claires et pédagogiques.
- Vérifier la significativité des relations entre variables par des tests statistiques.
- Rédiger un rapport complet et une présentation accessible à un public non technique.

---

## 🛠 Technologies utilisées

Le projet a été réalisé en Python à l’aide des bibliothèques suivantes :

- **Manipulation de données** : `pandas`, `numpy`
- **Visualisation** : `matplotlib`, `seaborn`, `missingno`
- **Statistiques & tests** : `scipy`, `statsmodels`
- **Machine Learning** : `scikit-learn` (`KNNImputer`, `RandomForestClassifier`, `PCA`, `Pipeline`, etc.)
- **Traitement & préparation** : `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`
- **Évaluation des modèles** : `accuracy_score`, `classification_report`, `confusion_matrix`

---

##  Structure du projet

- notebook.ipynb           # Notebook d'analyse et de traitement des données
- presentation.pptx        # Présentation synthétique à destination du client

