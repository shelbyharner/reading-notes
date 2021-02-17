## Chart.js API

  - Charts/tables are a simple and easy way to display data on a page.
  - Chart.js is a JavaScript plugin that uses HTML to draw the graph on the page.
    - Makes bar charts, line charts, pie charts, etc.
  - Download Chart.js from GitHub releases or use Chart.js CDN

  - canvas tag is utilized to create the chart element
  - requires fallback content for older browsers to read that do not support canvas
  - requires a closing tag, unlike the img tag
  - canvas renders a fixed sized drawing surface on the page
  - canvas is blank until the method getContext() is used to render context and drawing function

  - the grid or coordinate space of the canvas is defined by pixels in the HTML
  - canvas supports drawing rectangles and paths (lists of points connected by lines)
    - triangles and circles can be drawn by using paths
  
  - Fill style color: sets the style when filling shapes
  - Stroke style color: sets the style for shapes outlines
  - Global alpha property assigns semi-transparent or translucence
  - Line width determines the thickness of a line
  - Line cap determines the end points of a line (butt, round, square)
  - Line join determines line connectivity (can create things like a zig zag)

  - Fill text fills text at a given x,y position
  - Stroke text strokes text at a given x,y position

  