---
layout: post
title: "Répertoire de modèles Schema.org / JSON-LD pour le milieu culturel"
date: 2022-12-23 15:50:00
tags: schema.org
categories: projets
author: "Christian Roy"
post_image: "/assets/images/blog/bot-verso.png"
excerpt: Une compilation des modèles de données structurées au format JSON-LD et utilisant le vocabulaire Schema.org auxquels A10s a contribué.
---

Depuis quelques années, le format JSON-LD et le vocabulaire Schema.org sont de plus en plus utilisés dans le secteur de la culture pour décrire et organiser les informations concernant par exemple des livres, des oeuvres et leurs contributeurs, ou des événements, sur le web. Ces technologies permettent de rendre les informations plus facilement lisibles et exploitables par les machines. Une analogie souvent utilisée dit que si le recto des pages web est rédigé pour les humains, le recto, qui contient les données structurées, s'adresse aux robots.

Dans certains cas, ces robots sont ceux des moteurs de recherche, notamment Google, qui utilise certaines données structurées pour enrichir sa présentation des résultats de recherche.

A10s a développé quelques modèles, ou gabarits, de données structurées dédiés aux entités de la culture au cours des dernières années. Ce billet servira à en garder la trace.

## Qu'est-ce que JSON-LD et Schema.org ?

JSON-LD (JavaScript Object Notation for Linked Data) est un format de données structurées qui permet de représenter et de partager des informations sur le web de manière claire et accessible. Il utilise une syntaxe proche de celle du JavaScript pour décrire les données de manière structurée, ce qui en facilite la lecture et l'interprétation par les machines.

Le vocabulaire Schema.org est un ensemble de termes et de concepts qui définissent les types de données et les relations entre elles. Il est utilisé pour décrire les informations sur le web de manière standardisée, afin de les rendre plus facilement compréhensibles par les machines.

En utilisant JSON-LD et Schema.org ensemble, les développeurs peuvent créer des modèles de données structurées qui sont faciles à lire et à utiliser par les machines.

## Pourquoi utiliser des gabarits de données structurées ?

Pour les développeurs web, il peut être tentant de développer leur propre modèle de données structurées à partir de zéro, en utilisant le vocabulaire Schema.org. Cependant, il y a différentes raisons pour lesquelles il est souvent plus judicieux d'utiliser des gabarits de données structurées plutôt que de tout développer à partir de rien.

Tout d'abord, le vocabulaire Schema.org est très vaste et complexe, avec de nombreux termes et concepts à prendre en compte. En utilisant un gabarit de données structurées, les développeurs peuvent éviter de devoir apprendre toute la structure de Schema.org et se concentrer plutôt sur la mise en œuvre de leur propre modèle de données.

De plus, en utilisant un gabarit de données structurées, les développeurs peuvent bénéficier de la travail et de l'expertise de personnes ayant déjà développé de tels modèles. Ils peuvent ainsi éviter de commettre des erreurs ou de passer du temps à résoudre des problèmes déjà connus par d'autres.

## Quelques gabarits développés par A10s

Nous avons développé les gabarits suivants au cours des dernières années, dans le cadre de différents projets.

|Nom|Contexte|Contenu|Comment l'obtenir|
|---|---|---|---|
|Gabarits de données structurées de La danse sur les routes du Québec|Développement du [site web de la DSR](https://ladansesurlesroutes.com/).|Gabarits pour les organisations, personnes, oeuvres et événements du secteur de la danse (facilement adaptables à d'autres secteurs)|[Code libre sur Github](https://github.com/a10s-ca/ladsr-ds)|
|Métadonnées descriptive de webdiffusion de spectacles|[Trousse de webdiffusion des TAI](https://duceppe.com/blogue/trousse-de-webdiffusion-des-theatre-associes-etape-2/)|Gabarit pour un événement de webdiffusion|Dans le [guide de bonnes pratiques](https://docs.google.com/document/d/1Iw4c5ZHvHfj3F3UMPVPESxLAzx_MZACCDPjITa48knA/edit) ou dans le [générateur de métadonnées](https://docs.google.com/spreadsheets/d/1zLOjeGtHF0wGwOPwoKAO0eVlfW6zOH4G1f_a-E8QKF0/edit#gid=0)|
|Diffusion vidéo d’un spectacle d’opéra|[Projet _Une Carmen pour tout le Québec_](https://www.operademontreal.com/nouvelles/carmen-sur-26-grands-ecrans-le-23-fevrier-2020) de l'Opéra de Montréal|Gabarit pour un événement de présentation d'une vidéo|[Code libre sur Github](https://github.com/brixlabs/meta-carmen)|
|Données structurées de livres|[Partenariat](https://tamis.ca/2022/11/23/partenariat-avec-la-cooperative-des-librairies-independantes-du-quebec-leslibraires-ca-et-etat-des-lieux-en-referencement-web-du-livre/) entre TAMIS et la coopérative des Librairies indépendantes du Québec|Données structurées décrivant des livres|À travers l'outil [TAMIS](https://tamis.ca/) ou [sur demande](/contact)|

Il est à noter l'approche des gabarits fait des petits! Les amis de [La culture crée](http://corpo.culturecreates.com/fr/index.html) se sont inspirés du format des gabarits développés avec la DSR pour élaborer [ceux du projet ArtsData](https://culturecreates.github.io/artsdata-data-model/gabarits-jsonld/README.html).

### &nbsp;

_L'image accompagnant ce texte a été créée par [DALL-E](https://openai.com/dall-e-2/)._
