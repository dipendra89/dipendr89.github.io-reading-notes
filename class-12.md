<strong>The < canvas > element</strong>

The < canvas > element is used to draw graphics on a web page.

< canvas id="tutorial" width="120" height="120">< /canvas >

< canvas > looks like < img > element, with the only difference being that it doesn’t have the src and alt attributes. It only has two attributes, width and height. 
The <canvas> element is better in terms of being able to define some fallback content when dealing with < video >, < audio >, < picture >.

In various cases, we need to express the data or information in a way that it is easy and clearer to users. One of the very popular ways is through graphical representation. 
That is why the topic we will be discussing in the class today is an interesting and an important one. Example:

function draw() {

  var canvas = document.getElementById('canvas');
  
  if (canvas.getContext) {
  
    var ctx = canvas.getContext('2d');
    
    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}

Not only that, when we apply styles and colors plus texts, you can take your web page to a whole another level.
