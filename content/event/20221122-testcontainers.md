---
title: "Testcontainers avec Spring Boot, PostgreSQL et PostGIS : Live Coding !"
# description: "* Summary of experience"
date: 2022-11-22T22:19:30+02:00
tags: [
    "docker","java","spring","postgreSQL"
]
event-date: 2022-09-19T22:14:00+02:00
draft: false
hideSpeaker: false
intro: "Le but de cette conférence est simple : du Live Coding pour démontrer la puissance de Testcontainers pour réaliser des tests unitaires de composants dépendant de services tiers (une base de données par exemple)."
# place: "" # emplacement de l'evenement
speakers: ["Sébastien Prunier"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
# youtube: "" # URL de la vidéo de la conférence
---
Le but de cette conférence est simple : du **Live Coding** pour démontrer la puissance de **Testcontainers** pour réaliser des tests unitaires de composants dépendant de services tiers (une base de données par exemple).

Dans notre cas, nous mettrons en place Testcontainers pour tester unitairement des `Repository` d'une application Spring Boot, accédant à une base de données PostgreSQL et manipulant des données géographiques avec l'extension PostGIS.