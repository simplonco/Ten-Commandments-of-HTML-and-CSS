# Ten Commandments of HTML and CSS!

## HTML Structure

- Indent (see the Atom package <https://atom.io/packages/atom-beautify> and the keyboard shortcut `Alt`+`Ctrl`+`B`)
- Don't forget to set a `<!DOCTYPE html>`, good `<meta>` markups and a beautiful `favicon` !
- Importance of comments `<!-- -->` to describe your source code !
- Remind also that the classic tags `id` and `class` names can't contain spaces, IDs have to be uniques, and CSS only contain classes.
- Use some cool HTML5 Tags, eg `<navbar>` or `<footer>` (<https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5>)
- Set a `data-src`and the `alt` attributes of your images.

## Content Structure Example

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

## Integration of CSS

- Do not use it inline in the HTML tags or in the header, but in a dedicated CSS file with the meta link:
```html
  <link rel="stylesheet" href="style.css" />
```
- Also look at <https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/mettre-en-place-le-css>
- Finish by learning basic CSS tricks: <http://adamschwartz.co/magic-of-css/> bonus: `@keyframe`

## Resources

- <http://mdo.github.io/code-guide/>
- <https://google.github.io/styleguide/htmlcssguide.xml>
