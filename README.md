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



<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>
