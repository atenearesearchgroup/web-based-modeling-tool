# ES6 capabilities
https://gojs.net/latest/intro/modules.html

# Good things
- Can implement transactions and undo:
    https://gojs.net/latest/intro/transactions.html

# Issues
- Oldstyle spaghetti code.
- I couldn't keep the distributions of objects as I positioned them when adding a new node to the graph. Everything seems to reset.
- Roles and relationship's names are displayed very unclear. They are autopositioned and maybe that would be difficult to manage to work differently.
- It works with canvas:
    - Canvas and it is slower than SVG: GoJS uses HTML5 canvas, which is raster-based, and composed of pixels (not shapes). The elements are just containers for graphics, and developers have to use scripting (in the diagramming – usually JavaScript) to make an action such as drawing.
    - Resolution-dependent, images on canvas may lose quality when enlarged or displayed on Retina Displays. SVG is designed to create vector graphics. Being scalable has the advantage (This can’t be done with HTML5 canvas-generated images.)    
