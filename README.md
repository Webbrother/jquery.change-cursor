jQuery changeCursor plugin
===

Plugin changes cursor before element. 
Useful when you need to use image bigger that 32x32px as cursor.

###Browsers support:
Working with all browsers except IE<9

###Demo
[Link](http://jsbin.com/bojegu)


###How to Use?

changeCursor depends on jQuery. Include them both in end of your HTML code:

```html
<script src="jquery.js" type="text/javascript"></script>
<script src="jquery.change-cursor.js" type="text/javascript"></script>
```

then in your code do:

```js
$('.my-class').changeCursor('myurl/img.png', dx, dy, zIndex);
```

dx, dy - coordinates of picture center 
* dx - from left
* dy - from top
* zIndex - z-index css style for cursor

###To do
* Chrome performance
* Different types of cursors support (.cur, char)
