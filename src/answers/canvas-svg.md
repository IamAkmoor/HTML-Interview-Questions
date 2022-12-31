## What is the difference between canvas and svg?

__SVG__ stands for Scalable Vector Graphics
SVG is used to define graphics for the Web. 

 - has better scalability. So it can be printed with high quality at any resolution
 - gives better performance with smaller number of objects or larger surface.
 - can be modified through script and CSS
 - is vector based and composed of shapes.
Support for event handlers
Best suited for applications with large rendering areas (Google Maps)
Slow rendering if complex (anything that uses the DOM a lot will be slow)
Not suited for game applications

__HTML Canvas__
 - has poor scalability. Hence it is not suitable for printing on higher resolution
 - gives better performance with smaller surface or larger number of objects.
 - can be modified through script only
 - is raster based and composed of pixel.
No support for event handlers
Poor text rendering capabilities
You can save the resulting image as .png or .jpg
Well suited for graphic-intensive games

Differences Between SVG and Canvas
SVG is a language for describing 2D graphics in XML.

Canvas draws 2D graphics, on the fly (with a JavaScript).

SVG is XML based, which means that every element is available within the SVG DOM. You can attach JavaScript event handlers for an element.

In SVG, each drawn shape is remembered as an object. If attributes of an SVG object are changed, the browser can automatically re-render the shape.

Canvas is rendered pixel by pixel. In canvas, once the graphic is drawn, it is forgotten by the browser. If its position should be changed, the entire scene needs to be redrawn, including any objects that might have been covered by the graphic.