# Class 3 notes

## When should you use an unordered list in your HTML document?

- The ul element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.  
- The ul and ol elements may be nested as deeply as desired. Moreover, the nested lists may alternate between ol and ul without restriction.  
- The ol and ul elements both represent a list of items. They differ in that, with the ol element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the ol element should be used, otherwise you can use ul.

## How do you change the bullet style of unordered list items?

- The list-style-type property specifies the type of list item marker.

ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}

## When should you use an ordered list vs an unorder list in your HTML document?

-  An unordered list ul is used to create a list of items in no particular order i.e. the order of items is not relevant. By default, the items in this list will be marked with bullets. Whereas, an ordered list ol is used to create a list of items in a specific order.  


## Describe two ways you can change the numbers on list items provided by an ordered list?

- 
Type	Description
type="1"	The list items will be numbered with numbers (default)  
type="A"	The list items will be numbered with uppercase letters  
type="a"	The list items will be numbered with lowercase letters  
type="I"	The list items will be numbered with uppercase roman numbers  
type="i"	The list items will be numbered with lowercase roman numbers  

## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

- When laying out a document, the browser's rendering engine represents each element as a rectangular box according to the standard CSS basic box model. CSS determines the size, position, and properties (color, background, border size, etc.) of these boxes.

- Every box is composed of four parts (or areas), defined by their respective edges: the content edge, padding edge, border edge, and margin edge.


## List and describe the four parts of an HTML elements box as referred to by the box model

- Content - The content of the box, where text and images appear  
- Padding - Clears an area around the content. The padding is transparent  
- Border - A border that goes around the padding and content  
- Margin - Clears an area outside the border. The margin is transparent  

## What data types can you store inside of an Array?

- Arrays are classified as Homogeneous Data Structures because they store elements of the same type. They can store numbers, strings, boolean values (true and false), characters, objects, and so on. But once you define the type of values that your array will store, all its elements must be of that same type.  

## Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

- I'm not sure if I had to guess then no. If it was you access the values with let people = 


## List five shorthand operators for assignment in javascript and describe what they do.

- Name	               Shorthand operator	            Meaning
Addition assignment         	x += f()            	x = x + f()
Subtraction assignment	      x -= f()	            x = x - f()
Multiplication assignment	    x *= f()	            x = x * f()
Division assignment	          x /= f()	            x = x / f()

## Read the code below and evaluate the last expression and explain what the result would be and why.

- false, my best guess. The logical assignment false throws me off. 

## Describe a real world example of when a conditional statement should be used in a JavaScript program.

- Thinking about whether or not you are hungry. If i am hungry i will eat else wait to eat. 

## Give an example of when a Loop is useful in JavaScript.

- Helpful when you want to display a message over and over. Asking questions until you get the answer your looking for. 

sources: https://www.w3schools.com/default.asp