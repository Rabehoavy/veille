# Développez des applications de bureau multi-plateformes avec JavaScript, HTML et CSS
Le framework Electron permet d'écrire des applications desktop multiplateformes en utilisant JavaScript, HTML et CSS. Il est basé sur Node.js et Chromium.

# Installation
npm install electron -g

# Créer le manifeste
npm init
npm install electron --save-dev

# Publier son application
* npm install electron-packager -g --save-dev
electron-packager . --all

Si vous obtenez une erreur comme Unable to infer name or version. Please specify a name and version., exécutez plutôt la commande suivante : electron-packager . --all --name "Un super nom" --version "1.0.0".

* npm install -g electron-builder
builders/electron-builder-dev.json

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

```javascript
{
  // ...
  "scripts": {
    // ...
    "build-dev": "electron-builder -c ./builders/electron-builder-dev.json --win",
  },
  //...
}
```


