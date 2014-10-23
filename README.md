jQuery changeCursor plugin
===

Plugin change cursor before element. 
Working with all browsers except IE<9

###How to Use?

changeCursor depends on jQuery. Include them both in end of your HTML code:

<pre>
<script src="jquery.js" type="text/javascript"></script>
<script src="jquery.change-cursor.js" type="text/javascript"></script>
</pre>

then in your code do:

<pre>
$('.my-class').changeCursor('myurl/img.png, dx, dy, zIndex);
</pre>


dx, dy - coordinates of picture center, dx from left, dy from top.
zIndex - z-index css style for cursor

####Designed by
 * [webbrother.net][2]

[2]: http://webbrother.net