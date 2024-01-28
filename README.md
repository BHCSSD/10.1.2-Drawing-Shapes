# U1D1-Drawing-Shapes
Graded
# Instructions  

 # ** The very basic intro to coding **

  Our goal today is very simple, learn to colour inside the lines. We will be using P5 for javascript 
  
This is what is known as a ‘library’ of Javascript. This means it is a subset (think British English, vs American English) of Javascript. In this case, it was written to work with a ‘canvas’ to make drawing, animating and user interaction simpler than just using regular Javascript.


  
  ## TODO part 1:
  1. Make a file with the name U1D1-Drawing-Shapes
  2. make `createCanvas(x, y)`; inside of `setup`. Set x to 400, and y to 400
  3. inside of `draw` set your background colour: `background(255);` what does the number change in for your background?
  4.  `background(r,g,b)` set each value r,g,b for anywhere between 0-255. 
        Goal: make the background the same colour as Baby Yoda

  5. Highlight line 18,19,20 and use the short cut `ctrl + /` uncomment out the `function mousePressed()` 
  - this code will print of the x,y coordinates for you inside of the Console
  5. underneath the `text("Quadrant 4", 220, 220)` draw a `square(h,x,y)` h= height/width of the square, and x,y= location in quadrant 1
  6. draw a rectangle using `rect(h,w,x,y)` this is like `square()`, but you can change the width. in quadrant 2
  7. draw a `circle()` in quadrant 3
  8. draw a `ellipse()` in quadrant 4


## You should have 1 square, 1 rectangle, 1 circle 1 elipse and baby yoda colour
  
  8. Use `fill()` and play around with changing each shape to a different colour 
  9. what does `stroke()` & `strokeWeight()` do?
  - use comments `//` to put your answer at the very top of the page
  10. beside each shape you drew write a comment `//` and write the "arguments" that go inside ie `//square(l , x, y) as a way to practice


## Once you are done, make sure you save. I will look for this exact file name, if I don't see it, you don't get marked. 

---
``` js
//how to draw shapes
  square(l, x, y);
  rect(l, w, x, y)
  line(startX, startY, endX, endY);
  circle(radius, x, y);
  ellipse(l, w, x, y);

//Big 3 shape settings  
  fill(r,g,b);
  stroke(r,g,b);
  strokeWeight(13)

// writing secret messages
  //  "Comment out" a line so the computer will not read your message as code
```
