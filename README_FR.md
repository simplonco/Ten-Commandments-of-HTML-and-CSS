# Les Dix Commandements du HTML et du CSS !

## Structure HTML

- Indenter (voir le package Atom <https://atom.io/packages/atom-beautify> et le raccourci clavier `Alt` +` Ctrl` + `B`)
- Ne pas oublier de mettre un `<DOCTYPE html!>`, les balises `<meta>` correctes et un beau `favicon`!
- Importance des commentaires `<!-- -->` Pour décrire votre code source!
- Se rappeler aussi que les noms des balises classiques `id` et` class` ne peuvent pas contenir des espaces, que les ID doivent être uniques et que le CSS doit contenir uniquement des classes.
- Utiliser un peu de balises HTML5 fraîches, par exemple `<navbar>` ou `<footer>` (<https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5>)
- Définir and les attributs `data-src` et `alt` de vos images.

## Example de Structure du Contenu

```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
        <title>Bootstrap 101 Template</title>

        <!-- Bootstrap -->
        <link href="css/bootstrap.min.css" rel="stylesheet">

        <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
        <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
        <!--[if lt IE 9]>
          <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
          <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->
      </head>
      <body>
        <h1>Hello, world!</h1>

        <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <!-- Include all compiled plugins (below), or include individual files as needed -->
        <script src="js/bootstrap.min.js"></script>
      </body>
    </html>
```

## Intégration du CSS

- Ne plus intégrer le CSS dans les balises HTML ou dans l'en-tête, mais dans un fichier CSS dédié avec le lien meta:
```html
  <link rel="stylesheet" href="style.css" />
```
- Regardez aussi <https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/mettre-en-place-le-css>
- Terminer par l'apprentissage des astuces CSS de base: <http://adamschwartz.co/magic-of-css/> bonus: `@keyframe`

## Pour aller plus loin

- Utiliser un Linter <https://atom.io/packages/linter-csslint>
- Google Page Speed <https://developers.google.com/speed/pagespeed/>
- W3C Validator <https://validator.w3.org/>

## Ressources

- <http://mdo.github.io/code-guide/>
- <https://google.github.io/styleguide/htmlcssguide.xml>
