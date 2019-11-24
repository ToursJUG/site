---
title: "Soirée cache et scalabilité"
# description: "* Summary of experience"
date: 2013-09-11T19:15:00+01:00
tags: [
    "",
]
event-date: 2019-11-24T23:36:16+01:00
draft: false
hideSpeaker: false
# intro: "* Introduction pour l'evenement"
place: "Cantine Numérique" # emplacement de l'evenement
speakers: ["Mathilde Lemée"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---

Comment diminuer le temps de traitement d’un batch ? 

Le temps d’exécution d'une requête ? 

Le cache est un des outils du développeur pour résoudre ses problématiques quotidiennes et les concepts qui gravitent autour sont nombreux. Si les mots Cache Aside, Write-Behind, Read-Through ne vous sont pas familiers, cela fait pourtant parti des architectures qu’il est facile à mettre en place et qui dans certains contextes peuvent diminuer de manière drastique la durée d’un batch ou d’une requête.

Nous aborderons également les différents moyens de scaler horizontalement et verticalement (réplication, miroir, partitionnement) en nous appuyant sur différentes librairies existantes (MongoDB, Cassandra, Bigmemory ...) …