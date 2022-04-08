# Images, Color and Text

## Images

Choosing Images for you Site

Images should:

* Be relevant
* Convey information
* Convey the right mood
Be instantly recognizable
Fit the color palette

`<img>` empty tag includes the following:

`<src>` - tells browser where to find the image
`<alt>` - provides description of image if you can’t see it. important for screen readers.
`<title>` - additional information about the image.

Specifying `<height>` and `<width>` in the html tag tells the browser how large the image will be. the rest of the html content will load leaving the right amount of space. (What is the current practice?)

Place images

before a paragraph - block elements appear on a new line
inside the start of a paragraph - inline sits within a block level and do not start a new line
in the middle of a paragraph - text flows around the image

Rules for creating images:

right format
right size
measure in pixels

JPEG - use if image has many colors
PNG - use when images have few colors or large areas of the same color. they use “flat colors” (logos, illustrations, and diagrams). use for images needing transparency
GIF - for images that contain animations

`<figure>` - contains images with captions. Use `<figcaption>` to create relevant caption to image.

## Color

Color can be specified using rib values, hex codes, or color names.

**saturation** - amount of gray in a color. max is no gray and minimum is mostly gray.

**brightness** - how much black is in a color. max is no black and minimum is mostly black.

**contrast** - important to consider if there is enough contrast for text to be legible.

`opacity` property specifies opacity of an element. value is between 0.0 and 1.0. 

## Text

`font-family` - specifies typeface

`font-size` - specifies font size. use pixels, percentages, or em.

`@font-face` - use a font not installed on the computer. specify `src` to a copy of the font to be downloaded. 

`font-weight` - normal or bold 

`font-style` - normal, italic, or oblique

`text-transform` - uppercase, lowercase, capitalize

`text-decoration` - none, underline, overlain, link-though, blink (animates to make text flash on and off - generally considered annoying)

`line-height` - sets height entire line of text. makes vertical gap between lines of text larger.

`letter-spacing` - control space between letters

`word-spacing` - control space between words

`text-align` - left, right, center, justify (every line in a `<p>` takes up full width of the box)

`vertical-align` - used with inline elements