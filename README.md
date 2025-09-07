## 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans:
getElementById -> A single element object which only by use id. 

getElementsByClassName -> An HTMLCollection which only by use class.

querySelector -> to select the first element within the document that matches a specified CSS selector. 

querySelectorAll ->  used to return a collection of an element's child elements that match a specified CSS selector(s), as a static NodeList object.

## 2.How do you create and insert a new element into the DOM?
Ans:
A new element -
1- createElement()
2- setAttribute()
3- createTextNode()
4- appendChild()

## 3.What is Event Bubbling and how does it work?
Ans:
Event bubbling is a phase of DOM event propagation where an event starts from the target element and then propagates upward through its ancestors, one by one, until it reaches the document object.
Event goes from child → parent → document.

## 4.What is Event Delegation in JavaScript? Why is it useful?
Ans:
Event delegation means putting one event listener on the parent so it can handle events for all the child elements, using bubbling.

## 5.What is the difference between preventDefault() and stopPropagation() methods?
Ans:
preventDefault() -> Stops the default browser action.
stopPropagation() -> Stops the event from moving to parent/child elements in the DOM tree.
