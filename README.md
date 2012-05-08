# jQuery.selectmultiple

Fed-up with the poor usability of the native HTML select mutiple element? If so, use **jQuery.selectmultiple** and allow users to understand how they can choose multiple options without using the `[Ctrl]` or `[Cmd]` key!

## Dependencies

* jQuery 1.7.2+
* jQuery UI 1.8.20+
  * jquery.ui.core.js
  * jquery.ui.mouse.js
  * jquery.ui.widget.js
  * jquery.ui.sortable.js

*NB: An older version of jQuery UI might work (no testing done). However, jQuery 1.7.0 will be required due to the new event based syntax.*

## Usage

Include the plugin-script along with the jQuery and the required jQuery UI dependencies (see above), e.g.

```html
<script src="lib/jquery-1.7.2.min.js"></script>
<script src="lib/jquery-ui-1.8.20.custom.min.js"></script>
<script src="jquery.selectmultiple.js"></script>
```

Then inside a javascript file (or inline in a script tag), call the ``selectmultiple()`` method on the wrapped set you wish to update, e.g.

```javascript
$('select[multiple]').selectmultiple();
```

## Notes

Any options passed to the widget, will be passed as options to the underlying sortable widget to allow for customization of that widget.

## Testing done

* Firefox 12.0 on Ubuntu 11.10
* Chromium 18.0.1025.168 on Ubuntu 11.10
