# Chart.js

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

## canvas

the <canvas.> element has only two attributes, width and height.

the <canvas.> element requires the closing tag (/<canvas.>).

### Drawing shapes with canvas

The grid >normally 1 unit in the grid corresponds to 1 pixel on the canvas.

+ Drawing rectangles

fillRect(x, y, width, height)
Draws a filled rectangle.

strokeRect(x, y, width, height)
    Draws a rectangular outline.

clearRect(x, y, width, height)
    Clears the specified rectangular area, making it fully transparent.

    Drawing paths

    beginPath()
    Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
    Methods to set different paths for objects.

closePath()
    Adds a straight line to the path, going to the start of the current sub-path.

stroke()
    Draws the shape by stroking its outline.

fill()
    Draws a solid shape by filling the path's content area.

### Applying styles and colors

fillStyle = color
    Sets the style used when filling shapes.

![css text style](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors/canvas_fillstyle.png)

strokeStyle = color
    Sets the style for shapes' outlines.

![css text style](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors/canvas_strokestyle.png)

### Drawing text

fillText(text, x, y [, maxWidth])
    Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])
    Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
