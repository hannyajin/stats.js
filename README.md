Info.js
========

#### JavaScript Text/Info display (based on stats.js look/theme) ####

This class provides a simple info box.

### Screenshots ###

### Usage ###

```javascript
var info = new Info();
info.setMode(0); // 0: info box 1, 1: info box 2

// Align top-left
info.domElement.style.position = 'absolute';
info.domElement.style.left = '0px';
info.domElement.style.top = '0px';

document.body.appendChild( stats.domElement );

setInterval( function () {

	info.setInfo1('Some text: ' + Math.floor( Math.random() * 10 ));

	info.setInfo2('Some text for\nthe other display mode');

}, 1000);
```


### Change Log ###

2014 04 10 - Forked from stats.js and cut out all the functionality for simple text displaying.
