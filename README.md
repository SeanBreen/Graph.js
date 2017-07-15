## Synopsis

Graph.js is a script that graphs the number of views your website recieves in a given month.

![Example graph](http://seanbreen.ninja/css/img/graph.png)

## Code Example

To use this script, you will need to implement your own way of adding the page views into your database, and your own way of pulling them and turning them into javascript variables.
You will need to store the month name and the number of page views for each day in that month, and store these as javascript variables as shown below

```html
<canvas id="graph" width="645px" height="300px"></canvas>
<script>
    var month = 'december';
    var pageHits = [100,134,263,90,0,12,56,28,409,23,453,232,43,54,343,391,74,111,300,1,7,30,90,400,33,1000,934,590,670,200,0];
</script>
<script src="graph.js"></script>
```

## Installation

Implementation is as simple as adding a canvas element with id "graph" with width 645px and height 300px, along with adding the script.
