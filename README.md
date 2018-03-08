# betterPageScroll
Simple page scroll plugin for jQuery

### Usage
First, embed `betterPageScroll.js` in your page.

Then, define the anchors for scrolling by adding the class `bps-anchor` to the designated elements.

Finally, initialize the plugin:
```javascript
$(document).ready(function(){
  $("body").betterPageScroll({
    scrollSpeed: 500,
    callback: function(){
      console.log("scrolled to an anchor point");
      alert("anchor point reached!");
    },
    useDisabledRanges: true,
    disabledRanges: [
      {
        start: 100,
        end: 300
      },
      {
        start: 500,
        end: 1000
      }
    ]
  });
});
```

### Options
`scrollSpeed`: Determines the speed of the scrolling animation in milliseconds. 

`callback`: Callback function executed after scrolling to an anchor.

`useDisabledRanges`: Enables the use of disabled ranges.

`disabledRanges`: Array of object containing start and end of ranges, for which there shall not be a scroll to an anchor.




### Examples
Check the samples folder for examples.
