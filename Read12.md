# ANIMATED CHARTS:
- it's better to use charts to display informations rather than using tabels, and below the steps for setting up a chart:
* download Charts.js.
* Drawing a line chart
* Drawing a pie chart
* Drawing a bar chart
# The <canvas> element: 
- it has 2 attributes width and height 
# Drawing shapes with canvas :
- Drawing rectangles: 
fillRect(x, y, width, height)
Draws a filled rectangle.
strokeRect(x, y, width, height)
Draws a rectangular outline.
clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent. 
- example :
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}

# Applying styles and colors: 
- Colors:
ctx.fillStyle = 'orange';
ctx.fillStyle = '#FFA500';
ctx.fillStyle = 'rgb(255, 165, 0)';
ctx.fillStyle = 'rgba(255, 165, 0, 1)';

- Transparency: globalAlpha = transparencyValue
# Drawing text
function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  ctx.font = '48px serif';
  ctx.fillText('Hello world', 10, 50);
}


