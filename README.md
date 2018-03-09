# ember-cli-display-deploy-target
An ember-cli addon for displaying applications current deploy target

``` js
// index.js
module.exports = {
  name: 'ember-cli-display-environment',

  contentFor(type, config) {
    if (type === 'environment') {
      return '<h1>' + config.environment + '</h1>';
    }
  }
};
```
