# CSS (Cascading Style Sheet)

CSS specifies how your page looks. CSS allows you to determine a theme (fonts, colors, etc) and the layout of your page.

CSS is only used for markup.

**External CSS** - change the look of an entire website with one file. Must be referenced within the `<link>` element inside the head section. External stylesheets must be saved with `.css` extension. 

**Internal CSS** - internal stylesheet, used if one HTML page ahas a unique style, defined within the `<style>` element in html

**Inline CSS** - used to apply style to a single element

CSS identifies an element and then applies style using properties.

For example:

h1  {

    color: brown;

    font-style: italic;

    border-height: 50px;

}

## Cascading Order

As implied by the name,  styles "cascade" in the virtual style sheet following these rules:

1. Inline Style (inside HTML)
2. External and Internal style sheets (referenced and linked in the head section)
3. Browser defaults

There are many different ways CSS can be applied. It is useful to have references available to help you get the theme you want. 

[w3schools - CSS Reference -  CSS Properties](https://www.w3schools.com/cssref/default.asp)

[Mozilla Developer Network - CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[Return Home](README.md)