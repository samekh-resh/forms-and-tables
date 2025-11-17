# forms-and-tables
Odin Project, On Ramp code for Forms and Tables
forms are highly critical for websites- act as a portal to the back end where the user provides data, to which we use to change their experience, create products, etc.

form element is similar to a div- where it is a container element

accepts to essential attributes- which is action and method
action- takes url value that tells the form where the data should be sent for processing. 

method- tells the browser which HTTP request method should be used to submit the form
    - GET and POST are the most common ones uesed

GET (method)- when we want to retrieve from the server
- when using google search, that is a get request which gets information. 

post (method) - when we want to change something on a server (like when a user makes an account or a payment, or wants to change their background color)


Form controls
- we need form control elements to colelct data
- all elements users interact with on the form (text/drop down,check boxes, numbers) 

input element- most versatile of all the form control elements
- accepts a type= (tells the browser what type of data it should expect and how to render it)

labels are necessary because they inform our users what type of data they are expected to enter, 
the for= is tied to the id of the input type, and it allows us to know which label is for wich input.

placeholder= allows for placeholder text which then gives an example of what data should be entered and the format. 

name= allows for the backend to know what each piece of data represents
- exists as a variable name for the the values that user put in. 
- form input should always have a name attribute, or it will be ignored. 

email inputs are specifically for email addresses. 
- it also validates if it is correctly formatted like an email. 

password inputs mask the data, entailing that it is covered for safety. 

number type only allows for numbers involved. 

textarea element allows for a large swatch of text to be put in, you can even crontrol the initial height and width of the text area with rows= / cols= attributes accordingly. 

selection elements can be used when you want the user to select a value from a predefined list


to create a dropdown, use the select element, with the name attribute

the option element has a value that is relative to the information in the option. 
- every option should have a value attribute (if not, whatever is intisde the tag will be used for context)

you can also splut the the list of optinos using the <optgroup> element
- usually need a label= which acts as a label.

Radio buttons are with the type="radio"
- they allow the user to create multiple options the user can pick from. 

radio buttons cannot have multiple selections, since they all have the same name=attribute

using the atribute checked will make that radio option the default choice. 

checkboxes are similar to radio, as they allow users to choose from a set or predetermined option,s but they can choose many
type="checkbox"

checked can be used with checkboxes too. 

the button element creates clickable buttons the user can interact with to submit forms or trigger actions. 

type="reset" makes the button reset

type="button" creates generic buttons

organizing form elements

<fieldset>: groups related for inputs into one logical unit. 
<legend>- give field sets a heading or caption, dictating what the inputs are for. 

use-case- using fieldset to group radio buttons while the legend communicates to the user what each option is for. 
