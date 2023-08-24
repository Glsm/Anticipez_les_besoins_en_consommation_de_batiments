# Anticipez les besoins en consommation de bâtiments

## Projet4 -Openclassrooms
&nbsp;
**Author:** Gulsum Kapanoglu

***
<img src="img/se.png">

## Description de projet!
En tant que membre de l'équipe en charge de la durabilité environnementale pour la ville de Seattle, notre objectif ambitieux est de parvenir à une neutralité en émissions de carbone d'ici 2050. Pour y parvenir, nous nous concentrons sur la réduction des émissions de CO2 et de la consommation d'énergie des bâtiments non destinés à l'habitation, qui jouent un rôle significatif dans notre empreinte carbone urbaine.

## Objectif de projets
L'objectif principal de ce projet est de développer des modèles de prédiction avancés pour estimer les émissions de CO2 et la consommation d'énergie des bâtiments non résidentiels à partir de données structurelles, permettant ainsi de prioriser nos actions de réduction des émissions. De plus, nous souhaitons évaluer l'utilité potentielle de l'indice "ENERGY STAR Score" pour améliorer nos prédictions tout en évitant les coûts et la complexité actuels de son calcul.

## Data
Les relevés détaillés recueillis par  agents en 2016 constituent une ressource inestimable pour ce projet. Ces données comprennent des informations sur la consommation d'énergie, les caractéristiques des bâtiments, les équipements utilisés, les activités commerciales et industrielles, ainsi que les émissions de CO2 associées. Nous utiliserons des techniques d'analyse statistique et de modélisation prédictive pour identifier les tendances, les corrélations et les facteurs déterminants.

Source des données : https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

## Méthodologie
- Mise en place d'un modèle d'apprentissage supervisé (régression) pour prévoir les consommations de bâtiments de la ville de Seattle
- Création d'un pipeline de nettoyage des données
- Entraînement de différents algorithmes de machine learning (GBoost, Random Forest Regressor)
- Optimisation des hyperparamètres
- Recherche d'importance des features
- Mise en place d'un modèle d'ensemble
- Mise en place d'une fonction de préparation des données et prédiction de consommation et émissions de C02.

## Conclusion
- Possibilité de prédire la consommation d’énergie de manière fiable (73% de variance expliquée)
- Possibilité de prédire les émissions de CO2 mais légèrement moins fiable (34% de variance expliquée)
- Score Energy Star : inutile à la prédiction

## Proposition d'amélioration
Rénover ces bâtiments sur le modèle des bâtiments à énergie positive


## Pour plus d'informations

Veuillez consulter mon analyse complète dans [mon Jupyter Notebook](./Notebook_prediction_émissions de CO2.ipynb) ou ma [présentation](./Presentation.pdf). Pour toute question supplémentaire, veuillez contacter avec moi à gulsumkapanoglu@gmail.com.



Ce travail a été réalisé lors du projet 4 de ma formation Centrale Supèlec et OpenClassrooms de Data Scientist.
## Compétences évaluées
- Mettre en place le modèle d'apprentissage supervisé adapté au problème métier
- Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé afin de l'améliorer
- Transformer les variables pertinentes d'un modèle d'apprentissage supervisé
- Évaluer les performances d’un modèle d'apprentissage supervisé
