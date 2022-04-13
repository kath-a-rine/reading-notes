# More CSS Layout

you cannot set height and width to inline elements.

BLock elements create new lines for themselves.

***flexbox***

* for one-dimensional layouts
* will align elements children next to eachother by default and stretch to same height
* child elements become flex items

***grid***

* control multi-axis layouts instead of single (like flexbox)
* `display: grid`
* `grid-template-columns: repeat (# of columns, # fr)`
  * `fr` unit - fraction of remaining space
* `gap` gap between columns
* `grid-row` and `grid-column` instruct first element in a grid to span columns

`inline-block` - flows inline with the text

`float` - instructs element to "float" in a direction (left, right, or inherit). siblings then wrap around the float item.

* `column-count` and `column-gap` - define number of columns and space between.
* `column-width` - use instead of setting number of columns. set width and columns will be created as viewport space allows.

***positioning*** - changes how element behaves and how it relates to other elements in the document. uses `position` property.

* default value of `static`. other options are `relative`, `absolute`, `fixed`, and `sticky`.

[CSS Podcast - 009: Layout](https://web.dev/learn/css/layout/)

[Class 4 Reading Notes - Layout](201/class-04.md)