# Ejercicio

Observa el fichero **src/app.js**. Queremos completar el código para seleccionar todas las palabras del arary _words_ tal que tengan por lo menos el número de letras igual al valor de la variable _minSize_

<img src="https://oscarm.tinytake.com/media/141b122?filename=1677875496795_TinyTake03-03-2023-09-31-34_638134722962483435.png&sub_type=thumbnail_preview&type=attachment&width=586&height=522" title="Powered by TinyTake Screen Capture"/><br><a href="https://www.tinytake.com">.</a>
**Gato** y **loro** no aparecen porque tienen menos de 5 letras, el valor de la variable _minSize_
Notar que las palabras están separadas por una coma y un espacio.

Nota: recomiendo quitar el Auto Save para este ejercicio, ya que después de salvar, todo el código es indentado de nuevo.

Cómo abrir el proyecto:
<img src="https://oscarm.tinytake.com/media/141b12a?filename=1677875673230_TinyTake03-03-2023-09-34-14_638134724726074188.png&sub_type=thumbnail_preview&type=attachment&width=1197&height=166" title="Powered by TinyTake Screen Capture"/><br><a href="https://www.tinytake.com">.</a>

## Bonus

Cambia el valor de _minSize_ y sigue comprobando que el ejercicio sigue funcionando. Ejemplo si cambiamos el valor de minSize = 9, solo debería aparecer la palabra "Orangután."

### Manual Installation

1. Remember to install the npm packages first:

```
$ npm install
```

2. Build and Start coding!

Build the application for the first time...

```
$ npm run start
```

And start coding your Vanilla.js application, update the `src/index.html`, `src/index.css` or `src/app.js` depending on your needs.

## FAQ

#### 1) How do I run my code?

- Type on the command line `$ npm run start` and type localhost on the browser.

#### 2) Where do I write my code?

It depends on the language, but you have `./src/js/app.js`, `./src/style/index.css` and `./isrc/index.html` respectively, you can add new `.html` as you please, just make sure to include import it on the index.js.

**Note:** remember that the JS workflow starts inside `window.onload`.

#### 3) I don't see my changes.

Everytime you change any file inside the `./src` folder the website public URL will automatically refresh the changes (it's a process called hot deploy)
Remember also to refresh cleaning the cache (command+shift+r on mac, control+shift+r on pc & linux)

#### 4) How do I include more images on my project?

Add them inside the `./src/assets/img` folder and import them from any of your JS files. E.g: `import "../assets/img/rigo-baby.jpg";`

#### 5) How do I include more JS files?

Just add the files into the JS folder and import the file/variables into your index.js. E.g: `import myVar from "./file2.js"`

#### 6) How do I publish the website?

This boilerplate is 100% compatible with the free github pages hosting. Publish your website by running:

```sh
$ npm run deploy
```

Very easy and in just one step! Push to your **master** branch and use the free hosting that comes with [GitHub pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages), the project is ready to be published. Remember to choose to run the Github Page from your master branch.
