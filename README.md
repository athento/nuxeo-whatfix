# Nuxeo Whatfix

## Synopsis

This Nuxeo plugin integrates [Whatfix](http://whatfix.com/) with Nuxeo, providing interactive help to users.

## Installation

In order to use this plugin, you must deploy it along with [nuxeo-js-addon-enabler](https://github.com/athento/nuxeo-js-addons-enabler) and add **whatfix.js** to the **custom-includes.xhtml** file.

``` xml
...
<!-- Include your own js files here from other plug-ins -->
<script type="text/javascript"
  src="#{baseURL}js/?scripts=whatfix.js%7Cother-plugin.js">
</script>
...
```

Then, you just have to modify the [whatfix.js](src/main/resources/web/nuxeo.war/scripts/whatfix.js) snippet with your own configuration.
