# markdown-cv

A curriculum vitae maintained in plain text and rendered to HTML and PDF using CSS.

For more details, see the [project page](http://elipapa.github.io/markdown-cv), or the blog post on [why I switched to markdown for my CV](http://elipapa.github.io/blog/why-i-switched-to-markdown-for-my-cv.html).

***

## Customization

Simply [fork the markdown-cv repo](https://github.com/elipapa/markdown-cv)

![](https://help.github.com/assets/images/help/repository/fork_button.jpg)

and edit the `index.md` file [directly in Github](https://help.github.com/articles/editing-files-in-your-repository/)

![](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png)

adding your skills, jobs and education.

![](https://help.github.com/assets/images/help/repository/edit-readme-light.png)

## Distribution

To transform your plain text CV into a beautiful and shareable HTML page, you have two options:

### I. Use Github Pages to publish it online

1. Delete the existing `gh-pages` branch from your fork. It will only contain this webpage. You can either use git or [the Github web interface](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/#deleting-a-branch).
2. Create a new branch called `gh-pages`.
3. Head to *yourusername*.github.io/markdown-cv to see your CV live.

Any change you want to make to your CV from then on would have to be done on the `gh-pages` branch and will be immediately rendered by Github Pages.

### II. Build it locally and print a PDF

1. To [install jekyll](https://jekyllrb.com/docs/installation/), run `gem install bundler jekyll` from the command line.
3. [Clone](https://help.github.com/en/articles/cloning-a-repository) your fork of markdown-cv to your local machine.
3. Type `jekyll serve` to render your CV at http://localhost:4000.
4. You can edit the `index.md` file and see the changes live in your browser.
5. To print a PDF, press <kbd>⌘</kbd> + <kbd>p</kbd>. Print and web CSS media queries should take care of the styling.

## Styling

The included CSS will render your CV in two styles:
s
1. `kjhealy` the original default, inspired by [kjhealy's vita
template](https://github.com/kjhealy/kjh-vita).
2. `davewhipp` is a tweaked version of `kjhealy`, with bigger fonts and dates
  right aligned.

To change the default style, simply change the variable in the
`_config.yml` file.

Any other styling is possible. More CSS style contributions and forks are welcome!

### Author

Eliseo Papa ([Twitter](http://twitter.com/elipapa)/[Github](http://github.com/elipapa)/[Website](https://elipapa.github.io)).

![Eliseo Papa](https://s.gravatar.com/avatar/eae1f0c01afda2bed9ce9cb88f6873f6?s=100)

### License

[MIT License](https://github.com/elipapa/markdown-cv/blob/master/LICENSE)

-

---

## Commentaires du projet

J’ai choisi de faire un CV afin d'appliquer plusieurs éléments vus en cours comme les titres, les listes, les liens hypertextes, l’image, ainsi que de la mise en forme comme le gras, l’italique et le surlignage. Le format du CV m’a permis d’expérimenter différentes structures tout en gardant un contenu dégagé et cohérent.

J'ai décidée de ne pas utiliser de tableau car, selon moi, il ne s’intégrait pas naturellement au CV, et complexifiait la lecture de la page. J’ai préféré utiliser des listes claires et une mise en page aérée.

J’ai surlignié les disciplines étudiées afin de faire ressortir les nombreux domaines de spécialisation de l'auteur du CV.

J’ai également intégré une image de profil depuis un lien externe, mais une copie de l'image a aussi été ajoutée au dossier.

Pour les liens hypertextes, des exemples fictifs vers des articles et des pages externes ont été utilisées afin d'utiliser le Markdown pour créer du texte cliquable.

J’ai inclus une adresse mail et un lien vers une page Wikipedia en utilisant des balises HTML <a> et du Markdown

Le site a été déployé grâce à GitHub au lien suivant : 
[https://linadrbt.github.io/markdown-cv/](https://linadrbt.github.io/markdown-cv/)
