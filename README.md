[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/kriss-kross-io/mdi-iconset-svg)

# \<mdi-iconset-svg\>

Iconset for the Material Design Icons collection

## Installation

``` bash
bower install --save kriss-kross-io/mdi-iconset-svg
```

## Usage

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="mdi-logo-iconset-svg.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<iron-icon icon="mdi-logo:polymer"></iron-icon>
```

The iconset has duplicate icons, and it's not recommended to import all the icons.
Alternative you can create your own iconset with only the required icons. This version of the [Polymer Iconset Generator](https://mdi-poly-icon.appspot.com/) includes all icons from `mdi-iconset-svg`.

1. Visit [https://mdi-poly-icon.appspot.com/](https://mdi-poly-icon.appspot.com/)
2. Select the icons you want to use in your app
3. Download the optimized <iron-iconset-svg> markup and create an HTML import for it
4. Load the import in your app and start using!

## Setup

### Prerequisites

Install [npm](https://www.npmjs.com/) (or install [Node](https://nodejs.org/en/download/)):

``` bash
curl -L https://www.npmjs.com/install.sh | sh
```

Install [bower](https://bower.io/):

``` bash
npm install -g bower
```

### Tools

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

``` bash
npm install -g polymer-cli
```

### Start the development server

This command serves the app at `http://localhost:8080/components/mdi-iconset-svg/` and provides basic URL
routing for the app:

``` bash
polymer serve
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
