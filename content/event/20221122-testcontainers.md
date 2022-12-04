---
title: "Testcontainers avec Spring Boot, PostgreSQL et PostGIS : Live Coding !"
# description: "* Summary of experience"
date: 2022-11-22T19:30:00+02:00
tags: [
    "docker","java","spring","postgreSQL"
]
event-date: 2022-09-19T19:30:00+02:00
draft: false
hideSpeaker: false
intro: "Le but de cette conférence est simple : du Live Coding pour démontrer la puissance de Testcontainers pour réaliser des tests unitaires de composants dépendant de services tiers (une base de données par exemple)."
place: "SII Tours" # emplacement de l'evenement
speakers: ["Sébastien Prunier"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [["Affiche de la soirée","202211122.pdf"]]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
eventbrite: "426059504447" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
after: "sii-after" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
# youtube: "" # URL de la vidéo de la conférence
---
Le but de ce talk est simple : du **Live Coding** afin de démontrer la puissance de **Testcontainers** pour réaliser des tests unitaires de composants dépendant de services tiers (une base de données par exemple). 

Après avoir présenté le contexte du projet qui m’a amené à utiliser Testcontainers et notre stratégie de tests, nous mettrons en place les tests unitaires des « `Repository` » d'une application Spring Boot, accédant à une base de données PostgreSQL et manipulant des données géographiques avec l'extension PostGIS.
