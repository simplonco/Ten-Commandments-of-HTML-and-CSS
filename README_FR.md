# Les Dix Commandements du HTML et du CSS !

## Structure HTML

- Indenter (voir le package Atom https://atom.io/packages/atom-beautify et le raccourci clavier `Alt` +` Ctrl` + `B`)
- Ne pas oublier de mettre un `<DOCTYPE html!>`, les balises `<meta>` correctes et un beau `favicon`!
- Importance des commentaires `<!-- -->` Pour décrire votre code source!
- Se rappeler aussi que les noms des balises classiques `id` et` class` ne peuvent pas contenir des espaces, que les ID doivent être uniques et que le CSS doit contenir uniquement des classes.
- Utiliser un peu de balises HTML5 fraîches, par exemple `<navbar>` ou `<footer>` (<https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5>)
- Définir and les attributs `data-src` et `alt` de vos images.

## Intégration du CSS

- Ne plus intégrer le CSS dans les balises HTML ou dans l'en-tête, mais dans un fichier CSS dédié avec le lien meta:
```html
  <link rel="stylesheet" href="style.css" />
```
- Regardez aussi <https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/mettre-en-place-le-css>
- Terminer par l'apprentissage des astuces CSS de base: http://adamschwartz.co/magic-of-css/ bonus: `@keyframe`

## Ressources

- <http://mdo.github.io/code-guide/>
- <https://google.github.io/styleguide/htmlcssguide.xml>
