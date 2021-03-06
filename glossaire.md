# Glossaire

C'est important de définir les outils utilisés.

## Définitions
### React
> React (aussi appelé React.js ou ReactJS) est
> une bibliothèque JavaScript libre développée par Facebook depuis 2013.
> Le but principal de cette bibliothèque est de faciliter
> la création d'application web monopage, via la création
> de composants dépendant d'un état et générant une page (ou portion) HTML
> à chaque changement d'état. -- [Wikipedia][wp:fr:React]

En gros, **React** permet la conception d'interfaces modulaires et
dynamiques, mais sans toucher directement au DOM.

On pourrait sans doute concevoir les mêmes applications avec **jQuery**,
mais cette dernière bibliothèque porte plus sur les aspects de bas
niveau comme le DOM. **React**, de son côté, porte sur des aspects de
haut niveau et une abstraction du DOM. C'est entre autre ce qui permet
sa plus grande modularité.

D'autres *frameworks* modernes sont aussi très populaire:

* [Angular][] version 1 et 2; voir aussi [Aurelia][]
* [Vue][] complet
* [Ember][] le plus mature
* [Riot][] peut-être pas très populaire, mais succinct

### Next.js
> *Next.js is a minimalistic framework for server-rendered
> React applications.* -- [GitHub][gh:next.js]

Traduction:

> Next.js est un *framework* minimaliste pour des applications React
> rendus sur le serveur.

**Next.js** fait aussi abstraction des outils qui servent
au développement et au déploiement d'applications en production.

La section suivante fait justemment un survol de ces outils.

## JavaScript en 2017
La première version de [JavaScript][] remonte à 1995. En 1997,
le langage était standardisé sous le nom ECMAScript et a évolué
jusqu'à la 6e édition, soit ES7 toujours en développement.

Les fureteurs supportent tous au moins ES5 publié en 2009 et la plupart
supportent maintenant ES6 publié en 2015. **Node** aussi supporte ES6.

### JSX
[JSX][] est une extension syntaxique au JavaScript qui ressemble à du HTML.

Le **JSX** est optionnel au **React**, bien qu'on puisse dire que c'est
son langage de *template* natif.

### Babel
[Babel][] est un transpilateur qui converti du code écrit dans une
version de **JavaScript** (ou du JSX) vers une autre
version de **JavaScript**. C'est ce qui permet d'écrire du code moderne
tout en supportant divers environnements (fureteurs, node).

### Webpack
[Webpack][] gère à la fois les fichiers JavaScript et CSS pour les
concaténer et en faire des *bundles*.

## Documents liés

* [Préambule][] - 20 ans de développement web
* [Glossaire][] - ce document
* [Introduction][] - commencez ici si vous êtes pressés
* [Avec Markdown][] - impact sur la taille du JavaScript produit

[Préambule]: <preambule.md>
[Introduction]: <intro.md>
[Avec Markdown]: <markdown.md>
[Glossaire]: <glossaire.md>
[next.js]: <https://zeit.co/blog/next2>
[React]: <https://facebook.github.io/react/>
[node.js]: <https://nodejs.org/>
[n-install]: <https://github.com/mklement0/n-install>
[wp:fr:React]: <https://fr.wikipedia.org/wiki/React_%28JavaScript%29>
[gh:next.js]: <https://github.com/zeit/next.js>
[Angular]: <https://angularjs.org/>
[Vue]: <http://vuejs.org/>
[Ember]: <https://emberjs.com/>
[Riot]: <http://riotjs.com/>
[Aurelia]: <http://aurelia.io/>
[JSX]: <https://facebook.github.io/jsx/>
[JavaScript]: <https://fr.wikipedia.org/wiki/JavaScript>
[Babel]: <http://babeljs.io/>
[Webpack]: <https://webpack.js.org/>
