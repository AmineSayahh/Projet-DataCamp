# Predict blood donation

Ce projet utilise des données recueillies à partir de la base de données des donneurs du centre de services de transfusion sanguine de la ville de Hsin-Chu à Taïwan. Le centre passe son bus de service de transfusion sanguine à une université de la ville de Hsin-Chu pour recueillir le sang donné environ tous les trois mois. L'ensemble de données, obtenu à partir du référentiel d'apprentissage automatique de l'UCI, consiste en un échantillon aléatoire de 748 donateurs. La tâche consiste à prédire si un donneur de sang fera un don dans une fenêtre de temps donnée. Le travail contient un processus complet de création de modèles : de l'inspection de l'ensemble de données à l'utilisation de la bibliothèque tpot pour automatiser votre pipeline d'apprentissage automatique.

![Blood!](https://media.tehrantimes.com/d/t/2021/06/14/4/3797016.jpg)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AmineSayahh/Projet-DataCamp/main)

# Project rundown 
* Inspection du fichier transfusion.data
* Chargement des données des dons de sang ::
* Inspection de la transfusion DataFrame pizza
* Création de la colonne cible
* Vérification de l'incidence cible
* Fractionnement de la transfusion en ensembles de données d'entraînement et de test
* Sélection du modèle à l'aide de TPOT
* Vérification de l'écart
* Normalisation des journaux
* Entraînement du modèle de régression linéaire


