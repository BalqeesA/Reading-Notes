

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.

## Form Structure

## <form>
Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

## action
Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

## method
Forms can be sent using one of two methods: get or post. With the get method, the values from the form are added to the end of the URL specified in the action attribute. The get method is ideal for:
●● short forms (such as search boxes)
●● when you are just retrieving data from the web server (not sending information that should be added to or deleted from a database)

With the post method the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:
●● allows users to upload a file
●● is very long
●● contains sensitive data (e.g. passwords)
●● adds information to, or deletes information from, a database If the method attribute is not used, the form data will be sent using the get method

## id
We look at the id attribute on page 183, but the value is used to identify the form distinctly from other elements on the page (and is often used by scripts — such as those that check you have entered information into fields that require values).

## Checkbox
<input>
type="checkbox"
Checkboxes allow users to select (and unselect) one or more options in answer to a question

name
The name attribute is sent to the server with the value of the option(s) the user selects. When a question provides users with options for answers in the form of checkboxes, the value of the name attribute should be the same for all of the buttons that answer that question.

value
The value attribute indicates the value sent to the server if this checkbox is checked.

checked
The checked attribute indicates that this box should be checked when the page loads. If used, its value should be checked.


## Drop Down Li st Box
<select>
A drop down list box (also known as a select box) allows users to select one option from a drop down list. The <select> element is used to create a drop down list box. It contains two or more <option> elements

name
The name attribute indicates the name of the form control being sent to the server, along with the value the user selected.

<option>
The <option> element is used to specify the options that the user can select from. The words between the opening <option> and closing </option> tags will
be shown to the user in the drop down box.

value
The <option> element uses the value attribute to indicate the value that is sent to the server along with the name of the control if this option is selected.

selected
The selected attribute can be used to indicate the option that should be selected when the page loads. The value of this attribute should be selected. If this attribute is not used, the first option will be shown when the page loads. If the user does not select an option, then the first item will be sent to the server as the value for this control. The function of the drop down list box is similar to that of the radio buttons (in that only one option can be selected). There are two key factors in choosing which to use:
1. If users need to see all options at a glance, radio buttons are better suited.
2. If there is a very long list of options (such as a list of countries), drop down list boxes work better.














