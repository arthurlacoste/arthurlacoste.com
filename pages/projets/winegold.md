---
layout: usecase
title: "List me"
permalink: /winegold/
tags: open source, nodejs, Electron, jQuery, Liquid
---

![xapture d'écran winegold]({{ site.url }}/img/winegold/winegold-capture.png)

### Définition du besoin

Winegold se veut être un couteau suisse, relai graphique en un clic du terminal, centré autour du fichier. L'idée est de pouvoir déclencher n'importe quel traitement autour de l'action de glisser déposer d'un fichier dans le logiciel : conversion, redimenssionement, envoi par FTP, etc.. Bref, tout ce qu'il est possible d'effectuer en ligne de commande se retrouve utilisable graphiquement.

Compilé pour Windows, macOS et GNU/Linux, le projet est actuellement en beta publique.

### Choix technique

L'application utilise nodeJS, couplé a [Electron] afin de créer une application desktop.

En ce qui concerne le front end, le projet est axé autour de l'utilisation de jQuery et [LiquidJS] pour le moteur de templating, avec [Semantic UI] pour le coeur des composants CSS.

[Electron]: https://github.com/electron/electron
[Express]: http://expressjs.com/fr/
[LiquidJS]: http://harttle.land/liquidjs/
[Semantic UI]: https://semantic-ui.com/

### Expérience utilisateur

Pour rendre l'interface la plus minimaliste possible, le choix de n'afficher qu'une zone de drag and drop a été choisie. Par la suite, lorsque l'utilisateur dépose un (ou plusieurs) fichier, un tableau prend sa place :

![demo gif winegold]({{ site.url }}/img/winegold/winegold-demo.gif)


### Open source

Le projet est accessible sur GitHub, je vous encourage vivement à proposer des modifications si vous le souhaitez, une liste de propositions de fonctionnalités est disponible [sur le dépôt du projet](https://github.com/arthurlacoste/winegold/blob/master/docs/todo.md).
