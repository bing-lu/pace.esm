# pace-es
An automatic web page progress bar.

------
updated version to works as an es module.
------

Pace will automatically monitor your Ajax requests, event loop lag, document ready state and elements on your page to decide on the progress.

If you use AMD or Browserify, require pace.js and call `pace.start()` as early in the loading process as is possible.

### [Demo](http://github.hubspot.com/pace/docs/welcome/)

### [Documentation](http://github.hubspot.com/pace/)

### Example

```html
<head>
  <script src="/pace-es/pace.js"></script>
  <link href="/pace-es/themes/pace-theme-barber-shop.css" rel="stylesheet" />
</head>
```
```React/Vue/Angular
import Pace from 'pace-es/pace.js';
```
