# Charts.js, Canvas

## Charts from [Easily Create Stunning Animated Chateds with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

Charts.js - "a JavaScript plugin that uses HTML5's canvas elements to draw \[a] graph onto the page"

download charts.js and create an htmlpage to import the script using the `<script>` tag. The script tag "recieves the context of the canvas."

Charts use the `<canvas>` tag regardless if their type: line, pie, bar. They are given an `id`, `width` and `height`. Data is added the chart in an object, using the bracket notation. The object can also contain CSS styling for the chart.

## Canvas API

[mdn - Basic usage of canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

The `<canvas>` element had two attributes: `width` and `height`. Fallback text between the tags will render for those whose browsers do not support `<canvas>`.

`<canvas>` uses a method called `getContext()` to get rendering context

[mdn - Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

`<canvas>` only supports rectangles and paths (lists of points connected by lines).

>`fillRect(x, y, width, height)` - Draws a filled rectangle.
>`strokeRect(x, y, width, height)` - Draws a rectangular outline.
>`clearRect(x, y, width, height)` - Clears the specified rectangular area, making it fully transparent.
>`beginPath()` - Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
>`closePath()` - Adds a straight line to the path, going to the start of the current sub-path.
>`stroke()` - Draws the shape by stroking its outline.
>`fill()` - Draws a solid shape by filling the path's content area.

[mdn - applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

`fillStyle = color` - sets style used

`strokeStyle = color` - sets style for shape outlines

[mdn - drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

`fillText(text, x, y [, maxWidth])` - fills text at (x,y) position

`strokeText(text, x, y [, maxWidth])` - strokes text at (x,y) position