<html> 
<head> 
<style> 
#container {
width: 500px;
height: 500px;
position: relative;
}
#left {
width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: 0px;
}
#right {
width: 500px;
height: 500px;
position: absolute;
left: 500px;
top: 0px;
}
#up {
width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: -500px;
}
#down {
width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: 500px;
}
</style> 
<script type="text/javascript"> 
function move(direction) {
var container = document.getElementById('container');
switch (direction) {
case 'left':
container.style.left = container.offsetLeft - 500 + 'px';
break;
case 'up':
container.style.top = container.offsetTop - 500 + 'px';
break;
case 'right':
container.style.left = container.offsetLeft + 500 + 'px';
break;
case 'down':
container.style.top = container.offsetTop + 500 + 'px';
break;
}
}
</script> 
</head> 
<body> 
<div id="container"> 
<div id="left" onclick="move('left')"></div> 
<div id="right" onclick="move('right')"></div> 
<div id="up" onclick="move('up')"></div> 
<div id="down" onclick="move('down')"></div> 
</div> 
</body> 
</html>

# left {

width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: 0px;
}

# right {

width: 500px;
height: 500px;
position: absolute;
left: 500px;
top: 0px;
}

# up {

width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: -500px;
}

# down {

width: 500px;
height: 500px;
position: absolute;
left: 0px;
top: 500px;
}
}

function move(direction) {
var container = document.getElementById('container');
switch (direction) {
case 'left':
container.style.left = container.offsetLeft - 500 + 'px';
break;
case 'up':
container.style.top = container.offsetTop - 500 + 'px';
break;
case 'right':
container.style.left = container.offsetLeft + 500 + 'px';
break;
case 'down':
container.style.top = container.offsetTop + 500 + 'px';
break;
}
}
}

</script>

</head>

<body>
<div id="container">
<div id="left" onclick="move('left')"></div>
<div id="right" onclick="move('right')"></div>
<div id="up" onclick="move('up')"></div>
<div id="down" onclick="move('down')"></div>
</div>
</body>

</html>
