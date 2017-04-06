# Introduction
Vous voulez concevoir un site web ou une application avec [React][]?
Excellent! Si vous avez déjà [node.js][] version 6 ou mieux,
vous aurez votre site **React** en moins de 30 secondes!
Si vous n'avez pas **node.js**, ça prendre 1-2 minutes de plus.

## Documents liés

* [Préambule][] - 20 ans de développement web
* [Introduction][] - ce document
* [Avec Markdown][] - impact sur la taille du JavaScript produit

## Prérequis

### JavaScript
Le langage de programmation utilisé est JavaScript, autant dans
les fureteurs (JavaScript client) que sur le serveur et pour les
outils de *build* avec **node.js**.

### Node
Vous aurez besoin de [node.js][] version 6 ou mieux (*long term support*).
Je recommande l'usage du gestionnaire **n** pour vous assurer d'avoir
une version récente de **node.js**. Pour installer **n** et
la version de **node.js** 6 la plus récente:

```
sudo aptitude install git build-essential # sur Debian/Ubuntu
curl -L https://git.io/n-install | bash -s -- lts
```

Vous devez vous relogguer ou ouvrir un autre terminal pour
que n soit disponible. Voir [n-install][] pour les détails.

Ceci installera **n** et **node.js** 6.x.y ainsi que **npm** 3.x.y.
**npm** est le gestionnaire de paquets **node.js** et sert à installer
les dépendances en JavaScript.

## Définitions
C'est important de définir les outils utilisés.

### React
> React (aussi appelé React.js ou ReactJS) est
> une bibliothèque JavaScript libre développée par Facebook depuis 2013.
> Le but principal de cette bibliothèque est de faciliter
> la création d'application web monopage, via la création
> de composants dépendant d'un état et générant une page (ou portion) HTML
> à chaque changement d'état. -- [Wikipedia][wp:fr:React]

### Next.js
> *Next.js is a minimalistic framework for server-rendered
> React applications.* -- [GitHub][gh:next.js]

Traduction:

> Next.js est un *framework* minimaliste pour des applications React
> rendus sur le serveur.

[Préambule]: <preambule.md>
[Introduction]: <intro.md>
[Avec Markdown]: <markdown.md>
[next.js]: <https://zeit.co/blog/next2>
[React]: <https://facebook.github.io/react/>
[node.js]: <https://nodejs.org/>
[n-install]: <https://github.com/mklement0/n-install>
[wp:fr:React]: <https://fr.wikipedia.org/wiki/React_%28JavaScript%29>
[gh:next.js]: <https://github.com/zeit/next.js>
