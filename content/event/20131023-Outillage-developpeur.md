---
title: "Soirée Outillage du développeur"
# description: "* Summary of experience"
date: 2013-10-23T19:15:00+01:00
tags: [
    "",
]
event-date: 2019-11-24T23:30:13+01:00
draft: false
hideSpeaker: true
# intro: "* Introduction pour l'evenement"
place: "Cantine Numérique" # emplacement de l'evenement
speakers: ["Michael Bitard", "Pierre Barnoux"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---

#### Automatisation du poste de développeur

Vous avez un projet où il faut 3 jours d'installation acharnée en suivant un wiki obsolète pour réussir à faire un premier commit ?

Vous n'osez plus mettre à jour votre poste depuis 2006 de peur de ne plus pouvoir travailler?

Vous en avez marre d'oublier de mettre à jour le wiki chaque fois qu'il faut installer quelque chose de nouveau pour votre projet?

C'est frustrant...

Vous automatisez "l'exécution de vos tests"/"les déploiements"/"plein de trucs" avec jenkins ?
Vous uniformisez vos cycles de vie avec maven/gradle/ant/make?

C'est agréable...

Pourquoi ne pas faire pareil avec les postes de dev?

Le but de cette présentation est de vous faire découvrir les outils utilisés dans notre équipe afin d'automatiser/isoler/uniformiser les projets.
Côté technique, je parlerai de chroot, puppet, ansible, et un tout petit peu de vagrant.

**Intervenant** : {{< speaker "Michael Bitard" >}}

#### Kata technique de refactoring

Votre IDE offre tout un ensemble de fonctionnalités permettant de modifier la structure de votre code en extrayant des constantes, des méthodes, des classes, renommant des variables, méthodes ou classes.....

La maitrise de ces fonctionnalités nous permet de gagner du temps dans notre travail quotidien. Mais qui dit maitrise, dit pratique voir entrainement. Pour cet entrainement, il existe un ensemble d'exercice appelé Kata.

Le but de présentation sera le kata Gilded Rose Inn, que David Gageot avait choisi pour sa session live coding de l'USI 2013, adapté à l'IDE Eclipse.

**Intervenant**: {{< speaker "Pierre Barnoux" >}}
