# JS Object Literals: the DOM

## Object Literals

Objects group together variables and functions. A variable is called a property when it is in an object. A function is called a method.

*literal notation* - object in curly backets. each key and value is separated by a colon, each property and method separated by a comma (except the last).

*dot notation* - nameOfObject.PropertyOrMethodName the period `.` is the operator.

## The Document Object Model (DOM)

From *JavaScript and jQuery* page 184:

>The DOM is neither part of HTML, nor part of JavaScript; it is a set of rules. It is implemented by all major browser makers and covers two primary areas:
>* Making a model of the HTML page - the DOM specifies the way in which the browser should structure this model using a DOM tree.
>* Accessing and changing the HTML page -  people call the DOM an **Application Programming Interface (API)**

The DOM tree has four types of nodes:

* document node
* element nodes
* attribute nodes
* text nodes

Move through the DOM using their `id` or `class`. DOM methods are a way of accessing elements on the DOM tree. From there you can change or update the element using properties.

a `nodeList` will be produced if there are multiple nodes available from the query.

[mdn web docs - Node Properties and Methods](https://developer.mozilla.org/en-US/docs/Web/API/Node)

**Cross-site Scripting Attacks (XSS)** (p. 229) - an attacker puts malicious code into a site. Use **validation** (limiting the user input) to defend against XSS.

## Primitive Values and Object References

Primitive value assigned to a variable

a variable assigned to an object contains a reference to the variable.

Primite values are *immutable* (cannot be changed) and object references are *mutable*