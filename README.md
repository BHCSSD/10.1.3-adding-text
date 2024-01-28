# 10-U1D1-adding-text-
# Instructions  

 # ** How to write them words **
  Our goal with this example is to make text and have it zoom past
  
  
  ## TODO:
  1. Make a new File
  2. Check your `createCanvas(x, y)` inside of `setup`. Set x to 600, and y to 400
  3. inside of the `draw` function set your background colour to an r,g,b: `background();`  0-255
  4. inside of the `draw` function add `text("WORDS GO HERE",x,y)` place it in the centre of your canvas
  5. Change the font size `textSize(12)` and make it big 
  6. add `noStroke()` in the line before your text, use a comment `//` to tell me what it does
  7. add`fill(r,g,b)` change the colour of the text
  8. inside of your `text()` set your x value to the variable `textX` (this was set on line 1 of the code, it is a variable)
  9. with the idea tha `textX` is a varibale and can be changed, how can you make the text scoot off the screen? hint: start with a new line `textX = textX` and use this to change the x value using grade 1 math.
  10. I was going to put the answer to #8 here, but I decided to be a bit mean... good luck
  11. to reset the text back to the other side you need an if statement. Copy and paste time:
  ``` js  
  if (   textX < -250     ){ // you will need to edit the textX  < -250 to work for you
    textX=500;// this is the starting position for X
    print("too far left");
    }
```
## TODO2:
1. make 2 new variables at the top of the screen 
2. make a new line of text at the bottom left corner of the screen
3. using your 2 variables make the text go up in a diagonal line to the other corner 


---
``` js
//how to draw text
  text("WORD",x,y)
  fill(r,g,b);
  stroke(r,g,b);
  noStroke()
  strokeWeight(13)

// writing secret messages
  //  "comment out" a line so the computer will not read your message as code
```
