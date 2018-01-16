---
layout: usecase
title: "List me"
permalink: /listme/
tags: open source, nodejs, lowdb
---

### Définition du besoin

List Me est une application open source au but simple : partager une liste publique entre amis, afin que chacun puisse voter son option favorite, et définir l'élément final qui sera choisi.

Le postulat de base était simple : prévoir le prochain film ou la prochaine série a regarder avec ma copine en nous permettant de pouvoir chacun proposer de nouveaux choix, de voter pour  ceux qui nous intéressent, pour finalement cocher les items une fois qu'ils ont été réalisés.

### Choix technique

L'application utilise nodeJS côté back end, et tout particulièrement [Express] pour la gestion des routes, [lowDB] en ce qui concerne la gestion des données, [shortid], et [slugme].

En ce qui concerne le front end, le projet est axé autour de l'utilisation de jQuery et [LiquidJS] pour le moteur de templating.

[Express]: http://expressjs.com/fr/
[lowDB]: http://typicode.github.io/lowdb/
[shortid]: https://github.com/dylang/shortid
[slugme]: https://irz.fr/slugme-permalien-javascript-slug
[LiquidJS]: http://harttle.land/liquidjs/

### Expérience utilisateur

Le but était de conserver une interface simple en diminuant autant que possible la friction, en créant une liste à partir de la saisie d'un élément et d'un clic. L'interface princiaple est donc minimaliste, se reposant essentiellement sur le formulaire et l'affichage/gestion de la liste.

### Charte graphique

Voici la palette de couleur utilisé pour le projet :

![charte graphique listme]({{ site.url }}/img/listme/palette-charte-graphique.svg)

Voici un visuel du logo :

![logo listme]({{ site.url }}/img/listme/listme.svg)

### Open source

Le code source est disponible sur GitHub, je vous encourage vivement à proposer des modifications si vous le souhaitez, une liste de propositions de fonctionnalités est disponible [sur cette page](https://listme.irz.fr/#features).
