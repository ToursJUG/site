---
title: "Un Nouveau Site Pour Le Jug"
description: "Le site du ToursJUG fait peau neuve !"
date: 2019-11-15T19:05:59+01:00
tags: [
    "",
]
draft: true
layout: "post"
author: "François"
---
Voilà, c'est fait, le JUG a enfin son nouveau site :)
Cela faisait un petit bout de temps que je voulais cette refonte, et quitter [xwiki](https://xwiki.com/fr/), qui a accompagné et hébergé le JUG depuis sa création et surtout qui faisait parti de la sphere du monde Java. Je remercie l'équipe de xwiki pour cette accompagnement (l'ancien site du Tours JUG est toujours dispponible [ici](http://xwiki.toursjug.org/) pour les nostalgique, le temps de récupérer tout l'historique des soirées).

> La question, c'était remplacer, mais par quoi ?

Un site piloté par un framework PHP ? Non merci. Sans compter qu'un framework comme wordpress doit être suivi régulièrement pour être à jour

Un site piloté avec framework JS ? idem.

Loin de moi l'idée de troller sur PHP ou JS... Quoi que... Mais non, c'était plutôt les postulats de base suivant :

* Le site du JUG n'est pas un site dynamic
* Une indexation par les moteurs de recherche facilité (oui, j'entends bien que maintenant, ceux-ci sont capable d'interpreter les scripts)
* Ecriture des événements & article facilitée et gestion par git
* Tenter un truc fun

Je me suis tourné vers la mouvance [JAMstack](https://jamstatic.fr/2019/02/07/c-est-quoi-la-jamstack/), mais pas avec du javascript pour le moteur (cf. plus haut), mon choix s'est porté vers [Hugo](https://gohugo.io/), petit moteur de génération de site statique écrit en go.
Je l'avais déjà experimenté avec mon site perso, vous écrive vos article en markdown ou asciidoc, et ils sont généré sous forme d'un ensemble de page HTML classique le tout piloté par le theme choisi.

Là, cela devient interressant...
Hugo vient avec beaucoup de thèmes, plus ou moins facilement modifiable, paramétrable.
Mais aucun qui ne soit satisfaisant au final.

Nous sommes développeurs ou non ? Donc je suis parti d'une feuille vierge ! Et là, les ennuis commençent.

Car Hugo est basé sur les [Go Template](https://golang.org/pkg/text/template/), autant dire que le formattage de la date assez particulier, la gestion des context, [la notation polonaise](https://fr.wikipedia.org/wiki/Notations_infix%C3%A9e,_pr%C3%A9fix%C3%A9e,_polonaise_et_postfix%C3%A9e) ne m'ont pas facilité la tache afin de tordre le machin pour obtenir ce que je voulais.
Sans compter, que le processus i18n pour les dates n'est pas forcement évident de prime abord.

***Mais au final, ce fut fun !***

Vous pouvez voir ce que cela donne dans le repository du theme: [ToursJUG/hugo-toursjug-theme](https://github.com/ToursJUG/hugo-toursjug-theme).
(N'hésitez pas à le forker, faire des issues)

Il reste beaucoup de choses à traiter (cf. les issues si cela vous interresse). Vous devriez voir le site évoluer tranquilement prochainement.

Mais si au final, le site vous parait claire et vous permette d'aller à l'essentiel, a savoir les prochaien soirées du JUG, alors mon objectif sera atteint.

*Stay tuned*