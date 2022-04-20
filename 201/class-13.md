# Local Storage

from [No. 7. The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)

HTML5 storage is a way for web pages to store key/value pairs locally, within the client browser. 

Data is stored based on named key, which is a string. Data can be retrieved with that named key.

`setItem` - will overwrite the value of a named key

`getItem` - will return null on a non-existant key

HTML5 stroage is accessed though the object `localStorage` on the global object `window`

> the `storage` event is fired on the `window` object whenever `setItem()`, `removeItem()`, or `clear()` is called.

*"Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it."*

[mdn - Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)