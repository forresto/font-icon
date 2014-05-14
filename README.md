# `<font-icon>`

`<font-icon>` custom element for [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) via [Polymer](http://www.polymer-project.org/).

## Use

`bower install forresto/font-icon`

It will download font-awesome and polymer dependencies. font-icon is set up to include font-awesome's css if both are in the same directory (`../font-awesome/`). If your setup is different, you'll have to change those paths.

1. Include `<link rel="import" href="bower_components/font-icon/font-icon.html">` in your html.
2. Use `<font-icon icon="beer"></font-icon>` where you want the icon.

Additional [fa- classes](http://fortawesome.github.io/Font-Awesome/examples/) can be specified like this: `<font-icon icon="spinner" classes="fa-spin fa-2x"></font-icon>`.