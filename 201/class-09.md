## Forms
Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information. HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.
Whether you are adding a simple search box to your website or you need to create more complicated insurance applications, HTML forms give you a set of elements to collect data from your users.


### Why Forms?
The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

#### Form Controls
There are several types of form controls that you can use to collect information from visitors to your site.


### Lists, Tables and Forms
There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.


## Events
When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. Scripts often respond to these events by updating the content of the web page (via the Document Object Model) which makes the page feel more interactive.

#### DIFFERENT EVENT TYPES
Here is a selection of the events that occur in the browser while you are browsing the web. Any of these events can be used to trigger a function in your JavaScript code.

### HOW EVENTS TRIGGER JAVASCRIPT CODE
When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling.

1
Select t he element node(s) you want the script to respond to. For example, if you want to trigger a function when a user clicks on a specific link, you need to get the DOM node for that link element. You do this using a DOM query .

2
Indicate which event on the selected node(s) will trigger the response. Programmers call this binding an event to a DOM node. The previous two pages showed a selection of the popular events that you can monitor for.

3
State the code you want to run when the event occurs. When the event occurs, on a specified element, it will trigger a function. This may be a named or an anonymous function.


Here you can see how event handling can be used to provide feedback to users filling in a registration form. It will show an error message if their username is too short.

1
SELECT ELEMENT
The element that users are interacting with is the text input where they enter the username.

2
SPECIFY EVENT
When users move out of the text input, it loses focus, and the blur event fires on this element.

3
CALL CODE
When the blur event fires on the username input, it will trigger a function called chec kUsername ().This function checks if the username is less than 5 characters.


































