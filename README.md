jCanvas
=======

A 2D HTML5 Canvas API

Example usage (blue circle):
  frame = "b,a:5:5:3:0:" + 2*Math.PI + ",fs:#00F,f,c";
  jCanvasDraw(canvas, ctx, frame);

Frame can use any of the following drawing commands

Drawing Commands:
  a  - arc
  at - arcTo
  b  - beginPath
  c  - closePath
  cs - clearRect
  cw - clear screen (via resetting width)
  f  - fill
  fs - fillStyle
  j  - lineJoin
  l  - lineTo
  m  - moveTo
  q  - quadraticCurveTo
  r  - fillRect
  s  - stroke
  ss - strokeStyle
  w  - lineWidth
  :  - Separate arguments
  ,  - Separate commands
  /  - Comment until next comma
