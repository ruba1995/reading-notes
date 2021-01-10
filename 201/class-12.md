## Chart.js API. :

it's amethod to display information insted of using tables 
it could be 

1- circle charts 

2- column charts 

[chartsImage](charts.png)


A great way to get started with charts is with Chart.js


## The <canvas> element :

it's look like img element but without src and alt attributes ; insted we use width and height .
and if we didn't specify them there values will be **300 pixels wide and 150 pixels high** .

## Required </canvas> tag :

it's need a closing tag unlike img tag .

## Drawing shapes with canvas :

**The grid** 

it's like a coordinating system used in the web page srarts from the top left corner with value (0,0).

now we can draw multibl shapes in canvas :

rectangles

paths

triangle

Lines

Arcs

Bezier and quadratic curves

Quadratic Bezier curves


## Applying styles and colors :

**Colors**

fillStyle = color

Sets the style used when filling shapes.


strokeStyle = color

Sets the style for shapes' outlines .

**Transparency**

globalAlpha = transparencyValue

Applies the specified transparency value to all future shapes drawn on the canvas. The value must be

between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.

**Line styles**

lineWidth = value

Sets the width of lines drawn in the future.

lineCap = type

Sets the appearance of the ends of lines.

lineJoin = type

Sets the appearance of the "corners" where lines meet.

miterLimit = value

Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick 

the junction becomes.

getLineDash()

Returns the current line dash pattern array containing an even number of non-negative numbers.

setLineDash(segments)

Sets the current line dash pattern.

lineDashOffset = value

Specifies where to start a dash array on a line.


