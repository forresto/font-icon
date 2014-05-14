# `<font-icon>`

`<font-icon>` custom element for [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) via [Polymer](http://www.polymer-project.org/).

## Use

`bower install forresto/font-icon`

It will download font-awesome and polymer dependencies. font-icon.html includes font-awesome's css to work with bower defaults (`../font-awesome/`). If your setup is different, you'll have to change the css path.

1. Include `@font-face` definition *
2. Include `<link rel="import" href="./bower_components/font-icon/font-icon.html">`
3. Use `<font-icon icon="beer"></font-icon>`

Additional [fa- classes](http://fortawesome.github.io/Font-Awesome/examples/) can be specified like this: `<font-icon icon="spinner" classes="fa-spin fa-2x"></font-icon>`.

*

    <style>
      @font-face {
        font-family: 'FontAwesome';
        src: url('./bower_components/font-awesome/fonts/fontawesome-webfont.eot?v=4.0.3');
        src: url('./bower_components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.0.3') format('embedded-opentype'), url('./bower_components/font-awesome/fonts/fontawesome-webfont.woff?v=4.0.3') format('woff'), url('./bower_components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.0.3') format('truetype'), url('./bower_components/font-awesome/fonts/fontawesome-webfont.svg?v=4.0.3#fontawesomeregular') format('svg');
        font-weight: normal;
        font-style: normal;
      }
    </style>
