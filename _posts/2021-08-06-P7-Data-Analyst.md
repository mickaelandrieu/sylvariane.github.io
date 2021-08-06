---
layout: post
title: Production d'une étude de marché
subtitle: A la découverte des statistiques et de la classification hiérarchique
thumbnail-img: /assets/img/chicken.jpg
tags: [projet, formation, analysis]
---
## Détail du projet

Dans ce projet, une entreprise souhaitait étendre son marché à l'international. Avant de se lancer, il faut réaliser une étude pour déterminer un groupe de pays intéressant pour s'y installer. Dans un premier temps, une méthode de classification est imposée : la classification ascendante hiérarchique avec 5 clusters. 

![P5_01_dendrogramme](https://user-images.githubusercontent.com/64648386/115586828-4421e700-a2cd-11eb-8aae-81364bba8d6d.jpg)

Le dendrogramme a permis d'obtenir 5 clusters qui ont été analysés par des tests de comparaison de moyennes.

![acp_kmeans](https://user-images.githubusercontent.com/64648386/115587335-dd50fd80-a2cd-11eb-8fe2-3d0a72c0a666.png)

En complément de ce qui était demandé dans le projet, une seconde étude utilisant un algorithme du K-Means a été réalisé. Les points des clusters du K-Means ont été projeté dans le premier plan d'une ACP pour permettre la visualisation des résultats obtenus avec cet algorithme.


## Compétences acquises : 
- la construction et la lecture d'un dendrogramme
- le test de l'adéquation à une loi par l'intermédiaire de tests statistiques (Kolmogorov-Smirnoff, Shapiro-Wilk, etc.)
- l'interprétation d'une analyse en composante principale.

## Le notebook :
- [Notebook](https://github.com/Sylvariane/production_etude_de_marche/blob/master/P5_02_code.ipynb)

Ce projet a été soutenu le 27 septembre 2020.

