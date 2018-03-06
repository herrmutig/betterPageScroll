# betterPageScroll
Simple page scroll plugin for jQuery

### Usage
First, embed `betterPageScroll.js` in your page.

Then, define the anchors for scrolling by adding the class `bps-anchor` to the designated elements.

Finally, initialize the plugin:
```javascript
$(document).ready(function(){
  $("body").betterPageScroll({
    scrollSpeed: 500
  });
});
```

### Options
`scrollSpeed`: Determines the speed of the scrolling animation in milliseconds. 

### Examples
Check the samples folder for examples.
