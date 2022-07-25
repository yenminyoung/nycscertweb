# CUNY Hunter College
### Computer Science Education, K-12
### Master's Program

## CSCI 70900: Programming in a High Level Language
SuperArrays
* [SuperArray class](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#programming/8/SuperArray.java)
* [SuperArray driver](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#programming/8/SuperArrayDriver.java)

<img width="323" alt="SuperArray_shell" src="https://user-images.githubusercontent.com/87947236/180841144-65749aba-c36d-421b-ae81-0c6d90efd89d.png">


## CSCI 70300: Data Structures in a High Level Language
Linked Lists
* [Driver](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#ds/LinkedLists/Driver.java)
* [Linked Lists](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#ds/LinkedLists/LinkedList.java)
* [Node](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#ds/LinkedLists/Node.java)

<img width="293" alt="image" src="https://user-images.githubusercontent.com/87947236/180841239-03e49bbe-dd5e-4038-b474-d308e395a4bf.png">


## SEDC 71900: Methods I: Advanced Study of Secondary Learning Environments for Teaching Computer Science
Live Coding
* [Live Code](https://replit.com/@yenminyoung/cohort-3-summer-work-yenminyoung#methods/02_livecode_LANGUAGE.js)
```
//Big Ideas: 
//1. Draw multiple circles, control position, size, color, outline width
//2. Getting comforable with syntax, tweaking intentionally
//3. Getting used to the coordinates and grid system

// Student prompt: Here is the Olympics logo. What do we need to know how to code in order to recreate it? (Make a list)

function setup() {                 //PROVIDE
  createCanvas(600, 500)           //PROVIDE
}

function draw() {
  background(230)                 //PROVIDE
  strokeWeight(1)
  stroke("black")
  text(mouseX + ", " + mouseY, 10, 10)
  
  noFill()
  strokeWeight(8)
  
  stroke("blue")
  ellipse(80, 200, 100, 100)        //PROVIDE
  //Must-Answer-Q: Explain what the four numbers represent. 
  stroke("gold")
  ellipse(140, 250, 100, 100)

  stroke("black")
  ellipse(195, 200, 100, 100)

  stroke("green")
  ellipse(255, 250, 100, 100)

  stroke("red")
  ellipse(310, 200, 100, 100)
}



// Paper Planning: Start with a paper where they draw the olympics logo down first, and identify the coordinates of the center, so that they can easily transfer their writing and planning into code.

// Must Answer Q: What does each number inside the ellipse function mean?
// Must Answer Q: How do you make an ellipse move to the right? Up or down?
// Must Answer Q: What exact point on/in the circle does the x, y coordinates represent? (the top of the circle? The center? etc.)

// Clarifying an Idea Q: When you want to control the color of a circle, do you put it before or after the ellipse function?
// Clarifying an Idea: Function setup() runs once. function draw() runs on an infinite loop.
// Clarifying an Idea: All the code has to go inside the { }. They are like the slices of bread at the ends of a sandwich.

// Deliberate error: Drawing two circles on top of each other and only 1 shows up
// Deliberate error: Color function goes after the circle and messes up the first ellipse called.

// Big Reveal? (Insight to more logical thinking): Circles in the same row will have the same y value
// Big Reveal: Shortcut for circles. if width and height are both 100, you can use a shorthand ellipse(x, y, 100) and just have 3 parameters instead of 4.

// Additional Info: createCanvas is needed. The two parameters represent the width and height.
// Additional Info: background(230) gives the background color. It can take 0 to 255. What kind of colors can you make for a background?
// Additional Info: there are other color commands such as fill() or noStroke();

// Exit Ticket: go back to Must Answer Q
// Exit Ticket: Given a code of an ellipse (or codes of multiple figures), draw the ellipse on this paper (predict the outcome of the diagram)


/*
  PROVIDE :: code snippets or comments you definitely want to provide
  STUDENT-PROMPT :: a specifically-worded question you want to ask, or a general solicitation for input, etc
  MUST-ANSWER-Q :: a question that must be resolved, that a majority of your class must understand before moving on
  BIG IDEA :: an introduction of a new topic, a connection to prior lesson or discussion for application here in code, etc.
  BEEG REVEAL :: this is gonna blow yer minds...
  DELIBERATE-ERROR :: specific code snippet or a general approach that is a bad fit for the situation, is flat-out wrong, or will lead to a compile- or run-time error, etc.
  FIRSTDRAFT :: code that will work for now, but which you intend to replace later
  REVISION vX :: better versions of firstdraft code...
*/
```

<!-- <img width="1003" alt="image" src="https://user-images.githubusercontent.com/87947236/180841310-195246be-1f1a-4f37-8dcb-bb48ab2d25d6.png"> -->
