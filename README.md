# js13k-path

A polygon drawer for JS (2D canvas) with a tiny ASCII output.

Used for my 2018 js13kgames entry Geoquiz2.

- Path editor: http://xem.github.io/js13k-path/editor.html

- Path drawer: http://xem.github.io/js13k-path

Decoder/drawer:

```js
c.beginPath();
c.moveTo(x=`×`[z="charCodeAt"]()*8,y=`Ð`[z]()*4);
for(i of"'/7//''w")j=i[z](),a=-(j>>3)*.39+4.72,d=(j&7)*4+4,c.lineTo(x+=d*Math.cos(a),y+=d*Math.sin(a))
c.closePath();
c.stroke();
```
