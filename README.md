# aggregation-dialog

A Polymer Element showing a set of aggregation-display elements in a styled-dialog.

### Example that runs elasticsearch queries
```html
<aggregation-dialog
  client="[[client]]"
  index-name="indexName"
  index-types='["indexType"]'
  process-request="[[processRequest]]"
  query-builder-config="[[queryBuilderConfig]]"
  search-parameters="[[searchParameters]]"
  aggregation-field="field"
  aggregation-name="aggregation"
  result-function="[[resultFunction]]"
  order-by="{{order}}"
  selected-ids="{{selected}}">
</aggregation-dialog>
```

### Example that runs ajax queries
```html
<aggregation-dialog
  aggregation-name="[[dataType]]"
  query-url="[[queryUrl]]"
  process-request="[[processRequest]]"
  result-function="[[resultFunction]]"
  search-function="[[searchFunction]]"
  search-parameters="[[searchParameters]]"
  order-by="{{order}}"
  selected-ids="{{selected}}">
</aggregation-dialog>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

