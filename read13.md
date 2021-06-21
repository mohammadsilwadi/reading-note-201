# Local Storage

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a 
string.

localStorage is a property that allows JavaScript sites and apps to save key-value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.

## Tracking Changes to the HTML5 Storage Area

The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

## Limitations in Current Browsers
“5 megabytes” is how much storage space each origin gets by default. This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification. 