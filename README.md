# Nuxeo Whatfix

## Synopsis

This Nuxeo plugin integrates [Whatfix](http://whatfix.com/) with Nuxeo, providing interactive help to users.

## Installation

In order to use this plugin, you must deploy it along with [nuxeo-js-addon-enabler](https://github.com/athento/nuxeo-js-addons-enabler) and add **whatfix.js** to the **custom-includes.xhtml** file.

``` javascript
...
var source = "#{baseURL}js/?scripts=";
// Include your own js file here from other plug-ins
var scripts = [ "whatfix.js", "other.js", "plugins.js" ];
var scriptsLength = scripts.length;
...
```

Then, you just have to modify the [whatfix.js](src/main/resources/web/nuxeo.war/scripts/whatfix.js) snippet with your own configuration.
