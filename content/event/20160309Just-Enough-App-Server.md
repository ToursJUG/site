---
title: "Just Enough App Server"
description: "* Summary of experience"
date: 2016-03-09T19:15:00+01:00
tags: [
    "",
]
event-date: 2019-11-24T18:22:04+01:00
draft: false
hideSpeaker: false
intro: "* Introduction pour l'evenement"
place: "Cantine Numérique" # emplacement de l'evenement
speakers: ["Antonio Goncalves"] # Tableau avec les nom des speakers entre " et séparé par des , et doit être identique au titre du speaker enregistré !
# docs: [[]] # Tableau donnant les liens vers les documents de la soirée hors affiche - exemple : [["L'inauguration","http://toursjug.cloud.xwiki.com/xwiki/bin/download/Meetings/20080409/InaugurationToursJUG.pdf"], ["Unitils et Selenium","Unitils-Selenium.pdf"]]
# eventbrite: "" # Id de l'inscription (la partie de l'URL sr trouvant après https://www.eventbrite.fr/e/ )
# after: "" # Id (title urlizé d'un after) utilisé pour peupler la section after d'un evvent (exemple : apside-after-01)
---
***Websphere ou Weblogic sont-ils appropriés pour votre projet ? Trop "gros" ?***

Jetty, Tomcat, suffisent-ils à répondre à vos besoins ? Trop "petits" ? 

Ni trop, ni trop peu. Ce qu'il vous faut c'est "juste assez de serveur" pour supporter uniquement le sous-ensemble d'APIs et de services dont votre application a besoin. 

Dans cette session je ferai l'état des lieux des serveurs d'applications Java EE (Weblogic, Websphere, JBoss, GlassFish), Profile Web (TomEE, Payara, Siwpass) et Servlet (Tomcat, Jetty, Undertow). Et pour vos besoins de microservices, je vous présenterai des solutions plus modulaires comme WildFly Swarm, KumuluzEE, Spring Boot ou Dropwizard. Je vous parlerai de performance, de war, de jar executable, de monitoring, d'administration, d'optimisation, de cas d'utilisation et de retour d'experience... 

Tout ça en vous montrant du code et en faisant tourner plusieurs types d'applications (de la plus simple à la plus complexe) dans plusieurs sortes de containers... *et peut-être même sur un Raspberry Pi*.