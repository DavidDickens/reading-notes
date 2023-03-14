## Class 6 Notes

## How would you describe an object to a non-technical friend you grew up with?

- An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).

## What are some advantages to creating object literals?

- It provides a shorter syntax for creating/initializing properties from variables (Property Shorthand).  
- It provides a shorter syntax for defining function methods.  
- It enables the ability to have computed property names in an object's literal definition.  

## How do objects differ from arrays?

- Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- There are some important differences between dot and bracket notation:

- Dot notation:

- Property identifies can only be alphanumeric (and _ and $)  
- Property identifiers cannot start with a number.  
- Property identifiers cannot contain variables.  
- OK — obj.prop_1, obj.prop$  
-Not OK — obj.1prop, obj.prop name

-Bracket notation:

- Property identifiers have to be a String or a variable that references a String.
- It is okay to use variables, spaces, and Strings that start with numbers  
- OK — obj["1prop"], obj["prop name"]  

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

- Refers to the current object the code is being written inside   
- When you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create.

## What is the DOM?

- The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects
- The properties of all HTML elements
- The methods to access all HTML elements
- The events for all HTML elements
In other words: The HTML DOM is a standard for how to get, change, add, or delete HTML elements.  

## Briefly describe the relationship between the DOM and JavaScript.

- Document Object Model or DOM is an interface that defines how the browser reads your XML or HTML document. JavaScript is allowed to manipulate structure & style your webpage. Once the browser reads the HTML document, it creates a representational tree known as the Document Object Model.

https://canvas.instructure.com/courses/6214666/discussion_topics/17290588  