---
title: "DomainModel().stream() et continuous merge chez LesFurets.com"
description: "* Summary of experience"
date: 2016-01-27T19:15:00+01:00
tags: [
    "",
]
event-date: 2019-11-24T18:43:31+01:00
draft: false
hideSpeaker: true
intro: "* Introduction pour l'evenement"
place: "Cantine Numérique" # emplacement de l'evenement
speakers: ["Gilles Di Guglielmo", "Alexandre DuBreuil"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---

#### DomainModel().stream()

Pour faire du traitement de données, les listes, tableaux et maps sont les structures de données les plus faciles à manipuler. Malheureusement la plupart des applications sont conçues autour d'un modèle métier.

Chez LesFurets.com nous avons résolu ce problème en développant un KVM (Key Value Mapping). Ce framework est utilisé au cœur de l'application et cohabite avec le modèle métier. Grâce au mapping bidirectionnel de notre modèle métier vers un modèle clé-valeur, les manipulations de données deviennent extrêmement simples à réaliser. 

La mise en place de ce nouveau paradigme a nécessité un important refactoring de l'application et a permis de l'ouvrir à de nombreux outils actuels (Stream Java 8, RxJava, Spark, Cassandra)

Le projet est disponible sur GitHub: [github.com/lesfurets/model-map](https://github.com/lesfurets/model-map)

**Intervenant** : {{< speaker "Gilles Di Guglielmo" >}}

#### Continuous merge chez LesFurets.com

Nous allons faire un tour d'horizon de notre process de mise en production chez LesFurets.com pour comprendre comment nous arrivons à faire du continuous delivery, avec des mises en production tous les jours. 

Nous allons surtout parler de notre outil "git octopus", qui nous permet de faire du continuous merge, et de détecter en amont les problèmes de merge entre nos branches.

**Intervenant** : {{< speaker "Alexandre DuBreuil" >}}