# Projet OpenClassrooms "Participez à une compétition Kaggle"
### Sana TAYS

Lien vers la compétition : https://www.kaggle.com/competitions/store-sales-time-series-forecasting

Le but de ce projet est de prédire les ventes d'une liste de produits à travers le temps et selon différentes caractéristiques (localisation du magasin, jours de vacances, etc).

Pour cela, nous disposons d'un jeu de données d'entraînement et d'un certain volume de données relatives à la vente des produits.


Afin de répondre à la problématique, on réalise une étude comprenant les étapes usuelles de traitement et de nettoyage des données, de feature engineering, de visualisation, de modélisation, pour enfin soumettre notre prédiction sur les ventes à des dates hors du jeu d'entraînement.
La phase de modélisation suit une méthodologie jalonnée d'essais, c'est-à-dire que l'on teste différents modèles et on mesure leur performance.


Le premier modèle est un réseau LSTM très simple, souvent utilisé pour les séries temporelles, avec de l'optimisation d'hyperparamètre via Tensorflow.

Le second modèle est un modèle hybride entre une Régression linéaire et un modèle ensembliste XGBoost, également adapté à ce type de problématique.


L'ensemble de la démarche et des résultats est disponible dans le notebook du répertoire, accompagné d'un fichier zip contenant les données brutes.