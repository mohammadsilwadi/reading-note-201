# Object Literals

## WHAT IS AN OBJECT?

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

+ IN AN OBJECT: VARIABLES BECOME KNOWN AS **PROPERTIES** If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.

+ IN AN OBJECT: FUNCTIONS BECOME KNOWN AS **METHODS** If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.

  ![object](https://raw.githubusercontent.com/andrejrs/Object-Oriented-PHP/master/images/object.gif)

## Document Object Model (DOM)

The DOM specifies the way in which the browser should structure this model using a **DOM tree.**

As a browser loads a web page, it creates a model of t hat page. The model is called a **DOM tree**, and it is stored in the browsers' memory. It consists of four main types of nodes.

+ THE DOCUMENT NODE

  Every element, attribute, and piece of text in the HTML is represented by its own DOM node. At the top of the tree a document node is added; it represents the entire page (and also corresponds to the document object. When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree.

+ ELEMENT NODES

  HTML elements describe the structure of an HTML page. (The <hl' > -<h6'> elements describe what parts are headings; the <p'> tags indicate where paragraphs of text start and finish; and so on.) To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes.

+ ATTRIBUTE NODE

  The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. Attribute nodes are not children of the element thar carries them; they are part of that element. Once you access an element, there are specific JavaScript methods and properties to read or change that element's attributes. For example, it is common to change the values of cl ass attributes to trigger new CSS rules that affect their presentation.

+ TEXT NODES
 Once you have accessed an element node, you can then reach the text within t hat element. This is stored in its own text node. Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rat her a child of the containing element.  This illustrates how the text node is always a new branch of the DOM tree, and no further branches come off of it.

![ABC](https://user-images.githubusercontent.com/84705205/121782087-9508da00-cbb0-11eb-83dc-dbb6195ed236.png)

+ The browser represents the page using a DOM tree.
+ DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
+ You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
+ Whenever a DOM query can return more than one node, it will always return a Nade list.
+ From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
+ An element node can contain multiple text nodes and child elements that are siblings of each other.
+ In older browsers, implementation of the DOM is inconsistent.
+ Browsers offer tools for viewing the DOM tree .

## Problem Domain

