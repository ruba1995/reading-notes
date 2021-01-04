## Domain Modeling :

**Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.*



**Here's some tips to follow when building your own domain models.**

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.


## Table :

A table represents information in a grid format.

## Basic Table Structure :

- table 
- td (table column)
- tr (table row )
- th (table heading)



# Document Object Module (DOM):

it tell the browser how to build HTML page and how to let JS access and update the content of the page 
some people call it API , it consist of 4 parts .

- the document node 
- the attribute node 
- the element node 
- the text node 

[dom-tree](dom-tree.jpg)

**How we access the elements in the dom tree?**

**INDIVIDUAL ELEMENT*

- getElementById()
- querySelector()
- by traversing from one element to another within the DOM tree

**MULTIPLE ELEMENTS*

- getElementByClassName()
- getElementByTagName()
- querySelectorAll()

**TRAVERSING BETWEEN ELEMENT NODES*

- parentNode 
- previousSibl ing / nextSibl ing 
- firstChild / lastChild