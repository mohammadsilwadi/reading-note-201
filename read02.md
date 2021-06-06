




# **Basics of HTML**
### **Text**

#### 2 types of text markup 
* Structural markup: the elements that you can use to
describe both headings and paragraphs
- Semantic markup: which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on
#### Headings and paragraphs
h1>
h2>
h3>
h4>
h5>
h6>
HTML has six "levels" of
headings.
<p>
To create a paragraph, surround
the words that make up the
paragraph with an opening <p>
tag and closing </p> tag.

#### Bold, italic, emphasis
#### b>
By enclosing words in the tags
b> and /b> we can make
characters appear bold.
The b> element also represents
a section of text that would be
presented in a visually different
way (for example key words in a
paragraph) although the use of
the b> element does not imply
any additional meaning.
#### i>
By enclosing words in the tags
i> and /i> we can make
characters appear italic.
The i> element also represents
a section of text that would be
said in a different way from
surrounding content — such as
technical terms, names of ships,
foreign words, thoughts, or other
terms that would usually be
italicized.







#### Structural and semantic markup
### sup>
The sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.
### sub>
The sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.
# **Introducing CSS**
CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.
#### Example Styles
#### Boxes
Width and height
Borders (color, width, and style)
Background color and images
Position in the browser window.
#### Text
Typeface
Size
Color
Italics, bold, uppercase,
lowercase, small-caps
#### Specific
There are also specific ways
in which you can style certain
elements such as lists, tables,
and forms.
## **ccs**
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
## Using External CSS
link> external-css.html HTML
The link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the head> element.
It should use three attributes:
href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type
This attribute specifies the type
of document being linked to. The
value should be text/css.
rel
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.
## Using Internal CSS
style>
You can also include CSS rules
within an HTML page by placing
them inside a style> element,
which usually sits inside the
head> element of the page.
The style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css.
When building a site with more
than one page, you should use
an external CSS style sheet. This:
* Allows all pages to use the
same style rules (rather than
repeating them in each page).
* Keeps the content separate
from how the page looks.
- Means you can change the
styles used across all pages
by altering just one file
(rather than each individual
page).

# Basic JavaScript Instructions
### A script
 Will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
 ### A variable
 Is a good name for this
concept because the data stored
in a variable can change (or vary)
each time a script runs.

### we use let or var to assign a new variable.
# Decisions and Loops

![COMPARISON OPERATORS](https://www.pylenin.com/img/comparison-operators/comparison-table-2.png).

JavaScript Functions>A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it). JavaScript Function Syntax>>

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

Function nameOfTheFunction(parameter1){ statement }

nameOfTheFunction(value)>>>>>here we call the function by his name.
