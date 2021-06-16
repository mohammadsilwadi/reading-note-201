# **Layout**

HTML Layout Techniques

There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

    CSS framework
    CSS float property
    CSS flexbox
    CSS grid

CSS Frameworks

If you want to create your layout fast, you can use a CSS framework, like W3.CSS or Bootstrap.
CSS Float Layout

It is common to do entire web layouts using the CSS float property. Float is easy to learn - you just need to remember how the float and clear properties work. Disadvantages: Floating elements are tied to the document flow, which may harm the flexibility. Learn more about float in our CSS Float and Clear chapter.
HTML has several semantic elements that define the different parts of a web page:
HTML5 Semantic Elements. 

    <'header> - Defines a header for a document or a section
    <'nav> - Defines a set of navigation links
    <'section> - Defines a section in a document
    <article> - Defines an independent, self-contained content
    <'aside> - Defines content aside from the content (like a sidebar)
    <'footer> - Defines a footer for a document or a section
    <'details> - Defines additional details that the user can open and close on demand
    <'summary> - Defines a heading for the <details> element
![Box-Model](https://www.w3schools.com/html/img_sem_elements.gif)

## **Normal Flow**

In normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow.

### **Relative Positioning**

Relative positioning moves an
element in relation to where it
would have been in normal flow.

### **Absolute Positioning**

When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)

### **Fixed Positioning**

Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.
It positions the element in
relation to the browser window.
Therefore, when a user scrolls
down the page, it stays in the
exact same place. It is a good
idea to try this example in your
browser to see the effect.
