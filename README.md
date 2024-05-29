# index.html
style.css
html, body {
  margin: 0;
  padding: 0;
}
canvas {
  display: block;
}
sketch.js
function setup() {
  createCanvas(600,600);
  background("white")
}

function dfuraw() {
  stroke("yellow");
  fill("orange");
  
  
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 5, 5);
  }
}