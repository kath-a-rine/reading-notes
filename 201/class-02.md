# Basics of HTML, CSS, and JavaScript

## Text in HTML

**Structural markup** - elements to describe headings and paragraphs

**Semantic markup** - extra information - what is emphasized in a sentence,

**Headings** - six levels of headings

* `<h1>` - largest
* `<h2>`
* `<h3>`
* `<h4>`
* `<h5>`
* `<h6>`- smallest

`<p>` - paragraph

`<b>`- bold

`<i>` - italic

`<sup>` - superscript

`<sub>` - subscript

**White space collapsing** - when a browser displays only single line spaces, not the spaces in the code. Spaces and indents in code make it easier to read, but will not affect the page.

`<br />` - line break

`<hr />` - horizontal rule

Content management systems and html editors will have two views: ***visual editors and code views.***

Visual editor uses features similar to Word or Pages - allow you to markup without having to know code.

Code view shows you the code of the page you have made in the visual editor.

## Semantic markup

 Elements that add extra information to the page, but do not change the structure.

`<em>` - indicates emphasis

`<blockquote>` - indicates a block of text is a quote. Still uses `<p>` inside to indicate paragraph

`<strong>` - indicates importance

`<q>` - shorter quote within a paragraph

`<q>` and `<blockquote>` can use the cite attribute with a value of the url source.

`<abbr>` - abbreviation or acronym

`<cite>` - used when referencing a book or article title. Not used for names. Will render as italic.

`<dfn>` - define. Used when a new term or concept title is introduced.

`<address>` - contain author’s contact information

`<ins>` - inserted content. Usually underlined

`<del>` - deleted content. Usually strikethrough

`<s>` - indicates something is no longer accurate or relevant. Usually strikethrough

## Introducing CSS

CSS applies rules to HTML elements. A rule contains a selector and a declaration. Selector defines what element you will be applying the rule to. Declarations, with a property and a value, indicate how the element is styled.

**External CSS** - uses `<link>` element in HTML identifying the external CSS file to be used.

`<link>` will include *href* (path where file is), *type* (type of document), and *rel* (relationship- will be “stylesheet” with CSS files)

**Internal CSS** - uses `<style>` tag within the `<head>` element. Applies CSS within HTML

CSS selectors target specific elements within an HTML page.

[CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.asp )

## Basic JavaScript Instructions

**Statement** - individual steps or instructions

**Comments** - use comments in your code to explain what your code does.

`//` - used for single line comments
`/* */` - used for multi line comments or blocking out lines of code to prevent script from running.

**Variable** - data is stored in variables. Data can change each time a script runs. 

**Declare a variable** - create the variable and give it a name using `let` or `const`

Assign value to the named variable using `=` (*assignment operator*)

A variable is ***undefined*** until it is assigned a value

**Numeric Data** - numbers, not written in quotes

**String Data** - letters and characters set in matching quotes (single or double). Strings must always be in one line.

**Boolean Data** - `true` or `false`

***Rules for Naming Variables***

source: Duckett, Jon. *JavaScript & JQuery: interactive front-end web development* p. 69

1. The name must begin with a letter, dollar sign, or an underscore. It must not start with a number.

2. The name can contain letters, numbers, dollar sign, or an underscore. Note that you must not use a dash or a period in a variable name.

3. You cannot use keywords or reserved words.

4. All variables are case sensitive

5. Use a name that describes the kind of information that the variable stores.

6. useCamelCase

**Array** - stores a list of values. each item in an array is given a number (an index). Access items with the name and index number in square brackets.

## Decisions and Loops

**Conditional Statements** - if/then/else

[Comparison Operators - w3schools](https://www.w3schools.com/js/js_comparisons.asp)

Logical operators compare results of more than one comparison operator.

`&&` - logical and

`||` - logical or

`!` - logical not

## Things I want to know more about

- Where does the `<abbr>` title or cite with url source show up? only in the code?