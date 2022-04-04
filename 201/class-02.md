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