
Site de l'association des parents d'élèves des écoles de Bruges-Capbis-Mifaget.

C'est un site vitrine pour l'association, il sert à donner envie aux parents de devenir membre.
Il donne les informations sur les évènements organisés par l'association. 

Ce site fait deux pages

## Installation

1. Clonez le projet depuis le dépôt GitHub : https://github.com/SandrineOrieux/Eval-1-APE-Bruges.git

2. Accédez au répertoire du projet : cd Eval-1-ApeBruges

3. Installez les dépendances en utilisant npm : npm install

## Utilisation

1. Compilez les fichiers Sass en CSS : avec l'extension vsc Live Sass compiler cliquer sur Watch Sass.

2. Démarrez un serveur local pour visualiser le site : npm start


## Structure du projet

- `index.html` : Fichier HTML principal correspond à la page accueil.
- `event.html` : Fichier HTML secondaire correspond à la page évènement.
- `asset/style` : Répertoire contenant les fichiers CSS générés à partir des fichiers Sass et les fichiers sass. Il contient :
  -`_base.scss` : la surcouche de style des typos, variables et classes générales.
  -`_component.scss` : la surcouche de style des images, buttons, flèches.
  -`_custum.scss` : les variables modifiées de bootstrap.
  -`_layout.scss` : la surcouche de style du header, main, footer, menu de navigation et les grids.
  -`main.scss` : import des fichiers de style à compiler.
- `asset/img` : Répertoire pour les images et medias du site.


## Ressources

- [Documentation de Bootstrap](https://getbootstrap.com/docs/)
- [Documentation de Sass](https://sass-lang.com/documentation/)
- [Documentation de npm](https://docs.npmjs.com/)

## Contributeurs

- [Orieux Sandrine](https://github.com/SandrineOrieux)

