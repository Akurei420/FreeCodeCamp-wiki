# Trigger Click Events with jQuery
APIs - or Application Programming Interfaces - are tools that computers use to communicate with one another.

`$(document).ready()` This function makes it so all code inside of it only runs once our page loads.

Inside that you can add any function or code, for this particular waypoint you need to add a click handler:

```js
$("#getMessage").on("click", function(){

});
```
This will create a function so when the element with id `getMessage` is clicked, the custom function will be run.