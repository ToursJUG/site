---
title: "Tests de charge avec Gatling"
description: "* Summary of experience"
date: 2018-10-03T19:30:00+01:00
tags: [
    "",
]
event-date: 2019-11-24T11:17:38+01:00
draft: false
hideSpeaker: false
intro: "* Introduction pour l'evenement"
place: "HQ Tours" # emplacement de l'evenement
speakers: ["Stéphane LANDELLE"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---

#### *ou "Comment arrêter de croiser les doigts lorsqu'on passe en prod"*

Stéphane LANDELLE ([@slandelle](https://twitter.com/slandelle)) nous rend visite afin de nous présenter [Gatling](https://gatling.io/).

Face à l’explosion du traffic sur internet et la croissance exponentielle de l’économie numérique, la performance des applications devient un enjeu majeur des projets informatiques.

Pourtant, il est fréquent que les équipes adressent mal les tests de charges.

La première partie de cette présentation présente les concepts des tests de charges et leur méthodologie.

La seconde se focalise sur Gatling.

Gatling est un outil de test de charge open-source, utilisé pour générer des utilisateurs virtuels naviguant sur un site web.

Il se caractérise par:

* une architecture moderne et performante basée sur des IO non-bloquants et un modèle d’acteurs, vous permettant de générer un très grand nombre d’utilisateurs concurrents
* un DSL concis et lisible vous permettant d’écrire un code flexible et maintenable, plutôt qu’une interface graphique confuse
* des rapports élégants et aux métriques pertinentes