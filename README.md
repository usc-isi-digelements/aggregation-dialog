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

### Styling

`<aggregation-dialog>` provides the following custom properties and mixins for styling:

Custom property                                     | Description                                                         | Default
----------------------------------------------------|---------------------------------------------------------------------|--------
`--aggregation-dialog-bar-color`                    | The color of the single or left bars.                               | --paper-grey-300
`--aggregation-dialog-bar-count-color`              | The color of the single or left count labels.                       | --paper-grey-900
`--aggregation-dialog-bar-height`                   | The height of the single or left bars.                              | 20px
`--aggregation-dialog-bar-title-color`              | The color of the single or left title labels.                       | --paper-grey-900
`--aggregation-dialog-bar-title-hover-color`        | The color of the single or left title labels on hover (if a link).  | --paper-grey-600
`--aggregation-dialog-second-bar-color`             | The color of the right (second) bars.                               | --paper-grey-300
`--aggregation-dialog-second-bar-count-color`       | The color of the right (second) count labels.                       | --paper-grey-900
`--aggregation-dialog-second-bar-height`            | The height of the right (second) bars.                              | 20px
`--aggregation-dialog-second-bar-title-color`       | The color of the right (second) title labels.                       | --paper-grey-900
`--aggregation-dialog-second-bar-title-hover-color` | The color of the right (second) title labels on hover (if a link).  | --paper-grey-600

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

