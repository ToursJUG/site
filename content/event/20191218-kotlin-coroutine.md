---
title: "Débloquez la situation avec les coroutines de Kotlin"
# description: "* Summary of experience"
date: 2019-12-18T19:30:41+01:00
tags: [
    "",
]
event-date: 2019-11-25T22:48:41+01:00
draft: false
hideSpeaker: false
intro: "Bloqué par la complexité de votre code ? Trop de callbacks ou de threads ? Cas d'erreurs mal gérés ou non gérés ? Venez voir comment on débloque tout ça avec les coroutines de Kotlin !"
place: "Mame" # emplacement de l'evenement
speakers: ["Louis Cad"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
eventbrite: "billets-toursjug-debloquez-la-situation-avec-les-coroutines-de-kotlin-85400795077" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
after: "apside-after-01" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---

> Soirée organisée conjointement avec le [GDG Tours](https://www.meetup.com/fr-FR/GDG-Tours/).

Bloqué par la complexité de votre code ? Trop de callbacks ou de threads ? Cas d'erreurs mal gérés ou non gérés ? Venez voir comment on débloque tout ça avec les coroutines de Kotlin !

Si vous avez du code qui attend (I/O, événements, etc), les coroutines peuvent vous aider grandement.

Sur Android, c'est déjà une **révolution industrielle** en marche, mais Kotlin avec ses coroutines, est un langage multiplateforme qui fonctionne sur serveur, ordinateur… même sur montres WearOS et Apple Watch !

La promesse (tenue) des coroutines de Kotlin, c'est de rendre les fonctions non bloquantes aussi simples d'usages que les fonctions/méthodes bloquantes, y compris en ce qui concerne la gestion des erreurs.

En plus de ça, la concurrence structurée rend le parallélisme et l'annulation de traitements de tous types plus sûrs et très simples.

Dans ce talk, vous allez apprendre comment les coroutines s'utilisent, en quoi elles sont différentes, et **mieux conçues que les async/await** de certains autres langages.

Enfin, vous verrez une démonstration de coroutines dans une application native iOS 100% Kotlin, partageant du code avec une application Android, et peut-être plus…
