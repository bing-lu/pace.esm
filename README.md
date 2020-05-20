# pace-esm, an updated version of pace.js which works as an es module.

Pace will automatically monitor your Ajax requests, event loop lag, document ready state and elements on your page to decide on the progress.

If you use AMD or Browserify, require pace.js and call `pace.start()` as early in the loading process as is possible.

### [Demo](http://github.hubspot.com/pace/docs/welcome/)

### [Documentation](http://github.hubspot.com/pace/)

### Direct Reference Example

```html
<head>
  <script src="./pace-esm/pace.js"></script>
  <link href="./pace-esm/themes/pace-theme-barber-shop.css" rel="stylesheet" />
</head>
```

### Use with React/Vue/Angular
```html
import Pace from 'pace-esm/pace.js';
```
