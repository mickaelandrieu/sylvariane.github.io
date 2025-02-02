---
layout: post
title: Présenter des résultats
subtitle: Accès à l'éducation à travers le monde
thumbnail-img: /assets/img/school.jpg
tags: [projet, formation, analysis]
comments: true
---

## Présentation du projet

L'accès à l'éducation fait parti des droits de l'enfant. Malheureusement, on se rend que cet accès est très inégalitaire à travers le monde. Il existe de nombreuses associations qui viennent en aide aux enfants en difficulté mais il peut être intéressant de regarder les véritables raisons de cet accès inégalitaire. La plupart des aides existantes prennent la forme de financement. Est-ce que ces financements sont utiles ? On peut se poser cette question lorsqu'on se rend compte que subsiste les inégalités. 

Le but de cette étude est de créer des groupes de pays avec les mêmes problématiques pour pouvoir mieux étudier leurs caractéristiques. Par la suite, on pourra réfléchir à des méthodes au plus proche de leur problème.

La méthode choisie pour répondre à ce problème est la segmentation via des algorithmes d'apprentissage non-supervisée. Trois algorithmes ont été sélectionnées : l'algorithme du K-Means, la classification ascendante hiérarchique (dendrogramme) et l'algorithme DBSCAN. Face à notre problème, l'algorithme du K-Means avec un K = 4 semble la solution la plus appropriée.

![K-Means_K4](https://user-images.githubusercontent.com/64648386/115602142-e39ba580-a2de-11eb-92bf-2460d1257672.png)

Notre étude a pu nous permettre de déterminer deux groupes de pays "à risque" : 
- Un groupe de pays contenant des pays nouvellement indépendants où la situation financière n'est pas catastrophique ; 
- Un groupe de pays au coeur de nombreux conflits armés. 
Parmi les solutions à adopter, l'accompagnement des pays nouvellement indépendants et la fin des conflits dans les pays en guerre semble être des solutions plus adéquates. 

*Le rapport de ce projet est disponible en format pdf et un dashboard a été crée avec les différentes variables utilisées pour la réalisation de l'étude*: [DashBoard](https://public.tableau.com/views/Acceslducationtraverslemonde/Tableaudebord6?:language=fr&:display_count=y&:origin=viz_share_link)

## Compétences acquises dans ce projet

- Communiquer ses résultats à l'aide de visualisation
- Rédiger un rapport d'analyse statistique.


## Les notebooks

- [Notebook Nettoyage](https://github.com/Sylvariane/acces_education/blob/main/1_data_cleaning.ipynb), 
- [Notebook EDA](https://github.com/Sylvariane/acces_education/blob/main/2_data_EDA.ipynb), 
- [Notebook Modélisation](https://github.com/Sylvariane/acces_education/blob/main/3_data_modeling.ipynb)
- [Notebook Analyses des modèles](https://github.com/Sylvariane/acces_education/blob/main/4_Model_analysis.ipynb)

Ce projet a été soutenu et validé le 12 avril 2021.
