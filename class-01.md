# Introductory HTML and JavaScript

HTML and CSS are the foundations to web development. Every website uses HTML and CSS. Understanding HTML and CSS is foundational to understanding more advanced topics and languages.

**Browsers** - access websites though web browsers (IE (r.i.p.) Safari, Chrome…). Browsers interpret HTML and CSS code.

**Web servers** - host websites

**Screen readers** - read contents of a web page out loud.

## HTML Structure

HTML forms the structure of a webpage. Structure determines how a reader will understand a page. Heading and subheadings provide context for the paragraph text below.

**HTML elements** - characters inside angled brackets. Made up of **tags** (opening and usually closing). *Elements provide information about what is in-between the tags.*

>“Tags act like containers. They tell you something about the information that lies between their opening and closing tags.” - *Duckett, Jon. HTML & CSS: design and build websites (p. 22)*

Characters within the tags tell you the tags purpose.

Examples:

`<h1>This is a heading</h1>`

`<p>This is a paragraph.</p>`

>“Attributes provide additional information about the contents of an element.” - *Duckett, Jon. HTML & CSS: design and build websites (p. 25)*

Attributes are made up of a name and value sepated by an equal sign `=`.

**Attribute name** - what kind of information are you giving?

**Attribute value** - the information for the attribute. Placed within double quotes.

`<body>` - everything shown inside the browser window

`<head>` - holds information about the page. Contents are not shown on the page.

`<title>` - placed inside the `<head>` element, shown in the top of the browser or the tab in the browser. Usually holds the name of the webpage.

## Extra Markup

**DOCTYPES** - a declaration telling the browser which version of html the page is using. Will always be the first line of code. The DOCTYPE for HTML5 is `<!DOCTYPE html>`

**Comments in HTML** - comments are useful tools to have in code. Comments allow someone reading your code (or even yourself) how to understand your code. Comments will not be visible in the browser.

Comments are made using the following characters and format: `<! — comment text —>`

**ID attribute** - A unique identifier for an element. Can be used in any type of element. Allows you to style a specific element using its id. 

**Class attribute** - can identify several elements in your code. The value describes what class it belongs to. In CSS you can assign characteristics to different classes, affecting all elements within that class.

**Block elements** - start a new line in the browser. Examples of block level elements: `<h1>, <p>, <ul>, <li>.`

**Inline elements** - elements continue on the same line in the browser. Examples of inline elements: `<a>` (anchor), `<b>` (bold), `<em>` (italic), and `<img>` (image).

Use a `<div>` to group elements in one block-level box.

Use the `<span>` element to "contain a section of text where there is no other suitable element to differentiate from its surrounding text or to contain a number of inline elements." - *Duckett, Jon. HTML & CSS: design and build websites (p. 188)*

**iframe** - abbreviation of inline frame. content can be from any other html page. commonly used to imbed aGoogle  Map.

**`<meta>` element** - used inside the `<head>` element to contain information about the page.

**escape characters** - used in HTML to show specific characters such as an ampersand (&).

[Named character references - HTML living standard](https://html.spec.whatwg.org/multipage/named-characters.html#named-character-references)

## HTML5 Layout

HTML5 is the latest version of HTML and uses new elements to format your page content. Previously `<div>` was used heavily with id attributes. This change in HTML5 has created cleaner, easier to understand code.

Example HTML5 elements:

* `<header>`
* `<nav>`
* `<footer>`
* `<article>`
* `<section>`

## Process and Design

When building your site, it is important to understand who your audience is and what their motivation will be to visit your site.

**Sitemaps** - a diagram of your site showing how pages are grouped

**Wireframes** - a sketch of your webpage with its most basic content. A wireframe shows what goes where on your page. It will not include design such as colors or fonts.

## JavaScript and Computer Programming

JavaScript makes webpages interactive. It moves beyond what your page looks like and creates an experience for the user.

JavaScript has the ability to:

* Access content
* Modify content
* Program rules or instructions
* React to events

A *script* is a series of instructions a computer can follow. When writing a script it is important to look at the larger picture before digging into coding.

1. Define the goal
2. Design the script
3. Code each step

**Volcabulary** - words a computer understands

**Syntax** - how the vocabulary is assembled to create insturctions the computer can follow.

Computers complete or solve tasks ***programmatically.***

Computers require data to define the world we are trying to create.

**Objects** - the physical thing represented. Objects can have their own properties, methods, and events. Property names and values tell you about the object.

An **event** is when something occurs. A user clicking on a specific button is an example of an event. Events trigger specific pieces of code, all determined by the programmer.

**Methods** tell you something about an object and can "change the value of one or more of that object's properties." *(Duckett, Jon. JavaScript and JQuery: interactive front-end web development, p. 32)*

>Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other. ***Events can trigger methods, and methods can retrieve or update an object's properties.*** - *Duckett, Jon. JavaScript and JQuery: interactive front-end web development (p. 34)*

***HTML is the content of the webpage. CSS is how that content is presented. JavaScript is the action on the page.***

The `<script>` element is used in HTML to tell the browser when and where to load the JavaScript file.

## ***Things I want to know more about***

* Using id and class elements with CSS
* All things JavaScript
