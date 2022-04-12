# HTML Tables; JS Constructor Functions

## HTML Tables

* `<table>` - creates a table
* `<tr>` - indicates start of table
* `<td>` - a cell of the table
* `<th>` - table heading.
* `<colspan>` - indicates how many columns a cell should span. `<td colspan="2">` (spans across two columns)
* `<rowspan>` - how many rows a cell should span `<td rowspan="2">` (spans two rows)

To distinguish between main content and first and last rows:

* `<thead>` - table heading element
* `<tbody>` - table body element
* `<tfoot>` - table footer

## JS Constructor Functions

`new` keyword creates new object.

`let object name = new object;`

Use dot notation or square brackets to update value of properties.

use keyword `delete` to delete a property:

`delete objectName.propertyName`

*global scope* - function created not inside another object or function

`this` keyword refers to the function it is in.

a function inside of an object is a method.

**object model** - group of objects forming a model

**built-in objects**

* browser object model
  * the `window` object is the top level object refering to the browser window.
    * [mdn - Window](https://developer.mozilla.org/en-US/docs/Web/API/Window)
* document object model
  * `document` if the highest object
* global JS objects - group of individual objects related to JS language.
  * `String` `Number` `Boolean`
    * [mdn - String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
  * `Date` `Math` `Regex` (macthing patterns in strings of text)
    * [mdn - Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
    * [mdn - Math](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math)

## Domain Modeling

**Domain modeling** - creating a model in code for a specific problem

use a constructor function to define properites between many objects.

[Domain Modeling - Code Fellows](https://github.com/codefellows/domain_modeling#domain-modeling)

## Things I want to know more about

* combining arrays and objects.
* In yesterdays lab I was unable to format my arrays to show as single bullets and I wasn't sure how to then combine with the array of the hours open. I hope to learn how to format this today.
