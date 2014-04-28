# github calendar graph

a little javacript file using [d3.js](http://d3js.org) to show github contribution calendar graph using own data.

## dependency

d3.js

## usage

```html
<svg id="svg" width="800" height="86">
</svg>
<script src="http://d3js.org/d3.v3.min.js"></script>
<script src="calendar_graph.js"></script>
<script type="text/javascript">
   window.onload = function(){
    var data = [0,1,2,3,4,3,2,4,4,0,0,2,1,4,5,1,5,3,2];
    show_calendar_graph("#svg",data);
  }
</script>
```
