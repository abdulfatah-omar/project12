# project12
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Intro to the DOM</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header id="header">Header</header>
    <main id="main">
      <p class="paragraph p1">Paragraph</p>
      <p class="paragraph p1">Paragraph</p>
      <p class="paragraph p2">Paragraph</p>
      <p class="paragraph p2">Paragraph</p>
    </main>
    <aside id="aside1">Aside</aside>
    <aside id="aside2">Aside</aside>
    <footer id="footer">Footer</footer>
  </div>

  <script src="script.js"></script

<title>light Dark mode</title>
</head>
<body>
  <div id=""element"light and dark mode">element</div>

  <title>Animation</title>
</head>
</body>
div id ="element"Animation">element</div>
  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script>
 
<button id="stop">Stop sliding</button>

<div id="flip">Click to slide down panel</div>
<div id="panel">the lord of the ring </div>


</body>
</html>


*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

body { font-family: "Poppins", sans-serif; background-color: #f0f0f0; color: #333; transition: all 0.4s ease-in; }

h1 { text-align: center; margin-top: 1.25rem; }

.container { display: grid; width: 100%; min-height: calc(100vh - 4.25rem); place-content: center; gap: 1rem; text-align: center; }

#element {
    padding: 250px;
    font-size: 3rem;
    text-align: center;
}
.light{
    background-color: antiquewhite;
    color:black;
}
.dark{
    background-color: rgb(0, 0, 0);
    color: white;
}
section {
    background-color: #eee;
    padding: 5rem;
}
Shared in

<button>Click to fade in boxes</button><br><br>

<div id="div1" style="width:80px;height:80px;display:none;background-color:red;"></div><br>
<div id="div2" style="width:80px;height:80px;display:none;background-color:green;"></div><br>
<div id="div3" style="width:80px;height:80px;display:none;background-color:blue;"></div>



#panel, #flip {
  padding: 5px;
  font-size: 18px;
  text-align: center;
  background-color: #555;
  color: blue;
  border: solid 1px #666;
  border-radius: 3px;
}

#panel {
  padding: 50px;
  display: none;
}
</style>
</head>
<body> 

let currentIndex = 0;

function reset() { for (let i = 0; i < images.length; i++) { images[i].classList.remove('active'); } }

function initializeSlider() { reset(); images[currentIndex].classList.add('active'); }

function slideLeft() { reset(); currentIndex--; if (currentIndex < 0) { currentIndex = images.length - 1; } images[currentIndex].classList.add('active'); }

function slideRight() { reset(); currentIndex++; if (currentIndex >= images.length) { currentIndex = 0; } images[currentIndex].classList.add('active'); }

initializeSlider();

previousImage.addEventListener('click', function() { slideLeft(); });

nextImage.addEventListener('click', function() { slideRight(); });

const element = document.getElementById("element")
    
const section = document.getElementById("section")
const button = document.getElementById("button")
​
​
​
​
const Dark light  = () => {
    console.log("Dark light mode")
    element.classList.toggle("light")
    section.classList.toggle("dark")
   
}
button.addEventListener("dark light mode")

const = Animation 
console.log (Animation)
button.getAnimations{}

// Select container element and append an SVG with a height and width
const mouseChartElement = d3
  .select('#mouse-events')
  .append('svg')
  .attr('width', 500)
  .attr('height', 200)


// Create the circle
const mouseChartSVG = mouseChartElement
  .append("circle")
  .attr("cx", 100)
  .attr("cy", 50)
  .attr("r", 20)
  .style("fill", "red")


// Add a mouseover event to the circle
mouseChartSVG
  .on("mouseover", function() {
    d3.select(this)
      .style("fill", "blue")
  })
  .on("mouseout", function() {
    d3.select(this)
      .style("fill", "red")
  })

  

  $("#div1").fadeIn();
  $($(document).ready(function(){
$("button").click(function(){"#div2").fadeIn("slow");
  $("#div3").fa

  
 

  $(document).ready(function(){
    $("#flip").click(function(){
      $("#panel").slideDown(5000);
    });
    $("#stop").click(function(){
      $("#panel").stop();
    });
  });
