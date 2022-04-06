# HTML Lists, Control Flow with JS, and the CSS Box Model

## Lists

**Ordered List** - `<ol>` 

**Unorded List** - `<ul>`

Both `<ol>` and `<ul>` use `<li>` for their indiviual items in the list

**definition list** - `<dl>` used for lists containing definitions

`<dt>` - defined term

`<dd>` - contains the definition of the term

To create a nested list, you can put another `<ul>` with associated list items under an `<li>`.

## Boxes

CSS views HTML elements like boxes. Several properties can change how the box appears, where it is positioned, how any content appears within the box, and more.

**Border** - the edge of the box

**margin** - the space outside of the border.

**padding** - the space between the border and the box content

CSS can make content legibile on a variety of devices.

[mdn web docs_ - CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## Basic JS Instructions

***Arrays*** store a list of values separated by commas. Each value has an ***index*** number starting with 0 as the first index value.

## Decisions and Loops continued

**Switch statements** - a variable can have possible values indicated by `case`. The variable value determines which case is run. Each case followed by a `break` statement, stopping the rest of the statement from running. Switch statements include a default value if no cases match. All cases are in a single code block.

JS uses weak typing because the data type value can change. JS will interpret values and convert data to complete an operation. 

**Truthy** - treated as if they are true, can also be treated as 1

**falsey** - treated as if they are false, can also be treated as 0

Loops check conditions. If true the loop will stop running. If false it will move to the next instruction.

Types of loops:

* `for` - the most common loop. used to run code a specific number of times.
* `while` - use when the number of times the loop should run is unknown. will loop as long as the condition is true.
* `do...while` - will always run each statement even if false.

*keywords* - `break` (terminates thes loop) `continue` - "this keyword tells the interpreter to stop the current iteration, and then check the condition again." (duckett, Jon. JavaScript and JQuery. p 174)

for loops are used with arrays when you want the the same code to run through each array item.

## Things I want to know more about

* how `block` and `inline-block` work in CSS. examples only showed `inline`