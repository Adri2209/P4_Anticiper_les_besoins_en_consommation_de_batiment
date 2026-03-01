# 🏢 P4 – Anticiper les besoins en consommation énergétique des bâtiments  
**Ville de Seattle – Bâtiments non résidentiels**  
Formation Data Scientist – OpenClassrooms  

---

## 🎯 Contexte métier

La ville de Seattle s’est fixée un objectif ambitieux : devenir neutre en émissions carbone d’ici 2050.

Dans ce cadre, elle collecte des données détaillées sur la consommation énergétique et les émissions de CO₂ des bâtiments non résidentiels.

Ces relevés étant coûteux, l’objectif de ce projet est de :

- 🔹 Prédire la consommation totale d’énergie  
- 🔹 Prédire les émissions de CO₂  
- 🔹 Évaluer l’intérêt du ENERGY STAR Score  

à partir des seules données structurelles des bâtiments (taille, usage, année de construction, localisation…).

---

## 📊 Objectifs du projet

- Réaliser une analyse exploratoire des données (EDA)
- Nettoyer et préparer les données
- Effectuer du feature engineering
- Construire plusieurs modèles de régression
- Comparer au minimum 4 algorithmes de familles différentes
- Optimiser les hyperparamètres via validation croisée
- Évaluer rigoureusement les performances
- Mesurer la contribution du ENERGY STAR Score

---

## 🧹 Préparation des données

Principales étapes :

- Filtrage des bâtiments non résidentiels
- Suppression des bâtiments non conformes (ComplianceStatus)
- Gestion des valeurs manquantes
- Traitement des valeurs aberrantes
- Vérification des unités
- Transformation des variables (log, normalisation)
- Création de nouvelles variables structurelles
- Prévention de la fuite de données

Une attention particulière a été portée à la robustesse et à la reproductibilité du pipeline.

---

## 🔎 Analyse exploratoire

- Analyse des distributions (variables asymétriques)
- Étude des corrélations
- Identification des variables influentes
- Visualisations pour comprendre les relations entre variables et cibles

---

## 🤖 Modélisation Machine Learning

Deux variables cibles ont été modélisées :

- Consommation totale d’énergie
- Émissions de CO₂

### Modèles testés :

- Régression linéaire (baseline)
- ElasticNet
- Support Vector Regression (SVR)
- Random Forest
- Gradient Boosting

Les modèles ont été évalués via validation croisée.

Des pipelines Scikit-Learn ont été utilisés pour garantir la reproductibilité.

---

## 📈 Évaluation des performances

Métriques utilisées :

- R² (coefficient de détermination)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

Chaque choix technique a été validé via validation croisée.

---

## 🔍 Résultats clés

- Les modèles d’ensemble (Random Forest / Gradient Boosting) offrent les meilleures performances.
- La transformation logarithmique améliore la stabilité des prédictions.
- Les caractéristiques structurelles des bâtiments sont fortement prédictives.
- Le ENERGY STAR Score montre une contribution à adapter selon vos résultats.

---

## 💡 Conclusion

La prédiction de la consommation énergétique et des émissions de CO₂ est techniquement faisable à partir des données structurelles disponibles.

Ce projet démontre comment le Machine Learning peut :

- Réduire les coûts de collecte de données
- Identifier les bâtiments à fort impact environnemental
- Soutenir la stratégie carbone d’une collectivité

---

## 📁 Contenu du repository

- Notebook exploratoire
- Notebook prédiction CO₂
- Notebook prédiction énergie
- Présentation du projet

---

## 🛠 Technologies utilisées

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Validation croisée
- Pipelines ML

---

## 👩‍💻 Auteur

Adriana TINT  
Data Scientist – OpenClassrooms  