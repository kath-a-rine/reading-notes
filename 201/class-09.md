# Forms and JS Events

## Forms (Duckett, J. HTML and CSS p 144-175)

`<form>` - form controls are inside a form element

`<form action ="URL of page receiving information from the form" method="get or post">`

* `get` - for short forms. when you are getting data from a web server.
* `post` - form is long. users can upload data. contains sensitive data. adds or deletes information from a database.
* `id` - distinguishes form from other elements on a page.
* `file` - file upload followed by browse button
* `submit` - sends a form to a server. (ex. email list sign up)

`<input>` - creates form controls. `type` determines input. `name` tells the server what form control is recieving data. `maxlength` limits characters.

`textarea` - creates multiline text input

input types:

* `text`
* `password`
* `radio` - buttons to pick one of multiple options
* `checkbox`

`<select>` creates drop down boxes. `<option>` specifies dropdown selection options.

[mdn Web forms - Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms)

## Lists, Tables, and Forms (Duckett, J. HTML and CSS p 330-357)

[mdn - CSS Lists](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Lists_and_Counters)

`list-style-type` in CSS controls style of bullets on lists (or removes buttets if set to `none`)

`list-style-image` uses an image as a bullet

`list-style-position` - where the bullet marker sits. `outside` or `inside`

`list-style` is shorthand and can hold multiple properties.

[mdn - styling tables](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Styling_tables)

Tips for styling tables (from Duckett. p 338)

* give cells padding
* distinguish headings
* shade alternate rows
* align numerals

style `empty-cells` with `show`, `hide`, or `inherit` (if table is nested in another. will follow rules of containing table)

`border-spacing` specifies spacing between cells. horizontal followed by vertical.

`border-collapse` single borders for all cells where possible

## JS Events (Duckett, J. JavaScript and jQuery p 243-292)

scripts respond to events that occur in the browser. events can trigger code in response to user events. (see page 246 for list of event types)

>**Event handling** - steps that trigger JS code following user interaction

>1. select element nodes you want the script to respond to.
>2. indicate which event on those nodes will trigger the response. (binding an event to DOM node)
>3. state the code you want to run when the event occurs.

[mdn - event handling overview](https://developer.mozilla.org/en-US/docs/Web/Events/Event_handlers)

*DOM event handlers* - `element.event = functionName;`

*DOM event listeners* - `element.addEventListener('event', functionName [, Boolean (usually set to false)])`

## Things I want to know more about

* practice styling tables
* how and where the input data from forms is stored