# 10.1.2-Drawing-Shapes
Graded
# Instructions  

 # ** The very basic intro to coding **

  Our goal today is very simple, learn to colour inside the lines. We will be using P5 for javascript 
  
This is what is known as a ‘library’ of Javascript. This means it is a subset (think British English, vs American English) of Javascript. In this case, it was written to work with a ‘canvas’ to make drawing, animating and user interaction simpler than just using regular Javascript.


  
  ## TODO part 1:
  1. Make a file with the name U1D1-Drawing-Shapes
  2. make `createCanvas(x, y)`; inside of `setup`. Set x to 400, and y to 400
  3. inside of the `draw` curly brackets set your background colour: `background(255);` what does the number change in for your background?
  4.  `background(r,g,b)` set each value r,g,b for anywhere between 0-255. 
        Goal: make the background the same colour as Baby Yoda

  5. Highlight line 18,19,20 and use the short cut `ctrl + /` uncomment out the `function mousePressed()`
        - this code will print of the x,y coordinates for you inside of the Console
  5. draw a `square(x,y,h)` h= height/width of the square, and x,y= location in quadrant 1
  6. draw a rectangle using `rect(x,y,w,h)` this is like `square()`, but you can change the width. in quadrant 2
  7. draw a `circle()` in quadrant 3
  8. draw a `ellipse()` in quadrant 4


## You should have 1 square, 1 rectangle, 1 circle 1 ellipse and baby Yoda colour
  
  8. Use `fill()` and play around with changing each shape to a different colour 
  9. what does `stroke()` & `strokeWeight()` do?
  - use comments `//` to put your answer at the very top of the page
  10. beside each shape, you drew write a comment `//` and write the "arguments" that go inside ie `square(111 , 111, 50)// x,y,h as a way to practice and remember what each number does.
    - arguments are just another name for the numbers you put inside each shape. 

## Once you are done, make sure you save. I will look for this exact file name, if I don't see it, you aren't marked. 

// Starter Code

function setup() {
  createCanvas();
}// end setup do not delete anything here

function draw() {
  background();
  line(0, 200, 400, 200);// don't touch this
  line(200, 0, 200, 400);// don't touch this
  text("Quadrant 1", 20, 20);// don't touch this
  text("Quadrant 2", 220, 20);// don't touch this
  text("Quadrant 3", 20, 220);// don't touch this
  text("Quadrant 4", 220, 220);// don't touch this


  
}// end draw do not delete anything here

// function mousePressed() {
//   print(mouseX + ",   " + mouseY);
// }// end mouse pressed do not delete anything here

