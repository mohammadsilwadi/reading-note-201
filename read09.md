## Forms
 FORMS
Traditionally, the term 'form' has referred
to a printed document that contains
spaces for you to fill in information.
Form Controls 
There are several types of form controls that
you can use to collect information from visitors
to your site.
![css text style](https://img.brainkart.com/extra3/R1MVwxg.jpg)
 + ## <'form>
Form controls live inside a
<;form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.
> action
Every <'form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
> method
Forms can be sent using one of
two methods: get or post.
+ ## <'input'>
The <'input'> element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.

type="text"
When the type attribute has a
value of text, it creates a singleline
text input.

type="password"
When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
They are hidden in this way so
that if someone is looking over
the user's shoulder, they cannot
see sensitive data such as
passwords.

type="radio"
Radio buttons allow users to pick
just one of a number of options.


type="checkbox"
Checkboxes allow users to select
(and unselect) one or more
options in answer to a question.

type="checkbox"
Checkboxes allow users to select
(and unselect) one or more
options in answer to a question.

type="submit"
The submit button is used to
send a form to the server.

type="image"
If you want to use an image for
the submit button, you can give
the type attribute a value of
image.

type="date"
If you are asking the user for a
date, you can use an <input'>
element and give the type
attribute a value of date.
This will create a date input in
browsers that support the new
HMTL5 input types.

type="email"
If you ask a user for an email
address, you can use the email
input. Browsers that support
HTML5 validation will check
that the user has provided
information in the correct format
of an email address. Some smart
phones also optimize their
keyboard to display the keys you
are most likely to need when
entering an email address (such
as the @ symbol).

type="url"
A URL input can be used when
you are asking a user for a web
page address. Browsers that
support HTML5 validation will
check that the user has provided
information in the format of
a URL. Some smart phones
also optimize their keyboard to
display the keys you are most
likely to need when entering a
URL.

type="search"
If you want to create a single
line text box for search queries,
HTML5 provides a special
search input.

## Lists, Tables & Forms
###  Table Properties

You have already met several
properties that are commonly
used with tables. Here we will
put them together in a single
example using the following:
width to set the width of the
table

padding to set the space
between the border of each table
cell and its content
text-transform to convert the
content of the table headers to
uppercase

letter-spacing, font-size
to add additional styling to the
content of the table headers
border-top, border-bottom
to set borders above and below
the table headers .

text-align to align the writing
to the left of some table cells and
to the right of the others
background-color to change
the background color of the
alternating table rows. 

:hover to highlight a table row
when a user's mouse goes over it .

### Styling Forms
font-size sets the size of the
text entered by the user.
color sets the text color, and
background-color sets the
background color of the input.

border adds a border around
the edge of the input box, and
border-radius can be used
to create rounded corners (for
browsers that support this
property).

The :focus pseudo-class is
used to change the background
color of the text input when it
is being used, and the :hover
psuedo-class applies the same
styles when the user hovers over
them.

background-image adds a
background image to the box.
Because there is a different
image for each input, we are
using an attribute selector
looking for the value of the id
attribute on each input.

## Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

   + An HTML web page has finished loading
   + An HTML input field was changed
   + An HTML button was clicked

Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

![css text style](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events.