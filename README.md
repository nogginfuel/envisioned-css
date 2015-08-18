Envisioned CSS
=========
Edward Tufte uses a distinctive style in his handouts: simple, with well-set
typography, extensive sidenotes, and tight integration of graphics and
charts. `tufte-css` brings that style to HTML documents.

This project is directly inspired by and
based on [tufte-css](https://github.com/daveliepmann/tufte-css) and [tablesaw](https://github.com/filamentgroup/tablesaw)
[R Markdown Tufte Handout](http://rmarkdown.rstudio.com/examples/tufte-handout.pdf).

Getting Started
-
The file *index.html* is a self-describing demonstration document that walks through
the features of Envisioned CSS. The live version at
[nogginfuel.com/envisioned-css](http://nogginfuel.com/envisioned-css/)
is the best summary of the project.

To use Envisioned CSS on your own website, just copy `envisioned.css`, `tablesaw-bare.css`, `Roboto-Regular.ttf`, `RobotoCondensed-Regular.ttf` and `RobotoMono-Regular.ttf` to your project
directory (or just copy the folder structure) and add the following to your HTML doc's head block:

```html
<link rel="stylesheet" href="envisioned.css"/>
<link rel="stylesheet" href="tablesaw-bare.css"/>
```

Contributing
-
If you notice something wrong or broken, please open an
issue. **Pull requests are very welcome**.

For best results, keep pull requests to one change at a time, and
test your fix or new functionality against `index.html` on screens as
small as smart phones and as big as HD or HD+ displays. If you don't have a mobile device handy, fake different devices with your browser's developer tools.


Inspiration
-
 - [Dave Liepmann - Tufte CSS](https://github.com/daveliepmann/tufte-css)
 - [Filament Group - Tablesaw](https://github.com/filamentgroup/tablesaw)


License
-
The code is Released under the MIT license. *LICENSE.MD*.
The Roboto fonts are subject to the Apache 2.0 in the following directory font > Roboto folder > *LICENSE.TXT*.