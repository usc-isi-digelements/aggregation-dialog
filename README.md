# aggregation-dialog

A Polymer Element showing an aggregation-display element in a styled-dialog that automatically changes the data limit when opened.

### Example
```html
<aggregation-dialog
  show-checkboxes
  data="[[data]]"
  dialog-header="My Data"
  limit="{{limit}}"
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

