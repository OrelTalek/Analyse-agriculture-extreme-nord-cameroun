# Analyse-agriculture-extreme-nord-cameroun
Analyse des exploitations agricoles et de la sécurité alimentaire dans l'Extrême-Nord du Cameroun : nettoyage des données, analyse exploratoire, tests statistiques et modèles prédictifs sous R.
Projet réalisé dans le cadre du Bootcamp en analyse de données et initiation à la Data Science avec R. Il vise à identifier les facteurs qui influencent le rendement agricole et la vulnérabilité alimentaire des ménages.

Données : base de 2 215 observations et 35 variables après nettoyage.

Étapes du projet :

Diagnostic et nettoyage de la base (doublons, valeurs aberrantes, valeurs manquantes, modalités incohérentes).
Analyse exploratoire : rendement par culture, département et sexe, pluviométrie, revenu net.
Statistiques descriptives et tests : Shapiro-Wilk, Wilcoxon, Kruskal-Wallis, Chi-deux.
Modélisation : régression linéaire multiple (rendement) et régression logistique (vulnérabilité alimentaire, accuracy et AUC).
Comparaison de trois modèles (régression linéaire, Random Forest, Gradient Boosting) avec séparation entraînement/test et évaluation par RMSE et R².

Outils : R, RMarkdown, tidyverse, janitor, caret, randomForest, gbm, pROC.

Auteur : Talekeudjeu Fampah Orel Brayan
