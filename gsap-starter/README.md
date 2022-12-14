# Projet Affiche - GSAP Starter
---
## Contexte

Vous voulez travailler avec les technos suivantes :
- HTML
- CSS
- SASS
- JS
- GSAP

## Installation

1. Récupérer le projet via l'une des méthodes du tuto du README global
2. Dans le dossier `gsap-starter` (ou tout autre nom si vous l'avez modifié), ouvrir un terminal et rentrer la commande `npm install`. Cela aura pour effet d'installer tous les packages externes utiles au projet. Ici nous allons utiliser les modules SASS et GSAP, d'ailleurs on peut le voir dans le `package.json` (à part si vous comprenez ce que vous faites, merci de ne pas modifier ce fichier).
> ATTENTION : dans notre cas, `npm install` se lance une seule fois pour installer une bonne fois pour toute tous les modules. Vous n'avez pas a relancer la commande tous les matins en rouvrant le projet. 
3. Toujours dans le terminal, lancer la commande `npm run watch-sass`. Si on va voir dans le `package.json`, on peut voir que cette commande est un alias pour la commande `node-sass styles/scss/main.scss styles/css/main.css --watch`, je pense que cela devrait vous rappeler quelque chose !
4. Vous pouvez à présent écrire du code SCSS ! Mais veillez bien à garder le terminal ouvert avec la commande `npm run watch-sass` sinon...
> ATTENTION : l'endroit où vous codez est le dossier `styles/scss/`. Le dossier `styles/css/` est le dossier de compilation final que le navigateur pourra lire. D'ailleurs, si on va voir dans le fichier `index.html`, on peut voir qu'il pointe vers le fichier CSS dans `styles/css/`.
5. Dès que le titre s'anime sur la page c'est que l'on peut maintenant aussi utiliser la librairie GSAP !

## Documentation Officielle

- https://greensock.com/get-started/
- https://greensock.com/docs/

## Les tutos et formations

- https://grafikart.fr/tutoriels/greensock-animation-platform-415
- https://youtu.be/ruNc0Gx1kyc
- https://youtu.be/E5Jciq1VZng