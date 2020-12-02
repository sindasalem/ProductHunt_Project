# Outils de consommation de l'API ProductHunt

Il s'agit d'un outil connecté à l'API Product Hunt permettant de récupérer les produits sortis à une certaine date et d'en faire une visualisation.
Les principales fonctionnalités sont donc:
  - Choisir une date
  - Affichage de la liste des produits sortis à cette datte
  - Affichage d'un pie chart montrant la répartition du nombre de produits par catégorie.
## Cloner le repo
```sh
$ git clone https://github.com/sindasalem/ProductHunt_Project.git
$ cd ProductHunt_Project
```
## Partie Backend
* Technologie: [node.js]
* Call Rest API ProductHunt
### Installation & start
```sh
$ cd project-backend
$ npm install
$ npm run dev
```
Serveur Backend lancé sur le port 3000
## Partie Frontend
* Technologie: [angular]
* Affichage de la liste des produits sortis à la date choisie avec pagination
* Affichage d'un pie chart montrant la répartition du nombre de produits par catégorie(topic) (Les dix premières catégories ayant le plus de produits )
### Installation & start
```sh
$ cd project-frontend
$ npm install
$ ng serve
```
Serveur Frontend lancé sur le port 4200
## Naviguer sur http://localhost:4200/
[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Angular]: <http://angular.io>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
