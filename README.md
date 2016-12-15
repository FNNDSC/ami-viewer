# \<ami-viewer\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/fnndsc/ami-viewer)


Visualize medical imaging data

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="ami-viewer.html">
    <link rel="import" href="../ami-loader/ami-loader.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<ami-loader urls="{{urls}}" series="{{series}}"></ami-loader>
<ami-viewer series="[[series]]"> </ami-viewer>
```

## Documentation and demo
AMI Viewer Polymer element http://fnndsc.github.io/ami-viewer/  

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
