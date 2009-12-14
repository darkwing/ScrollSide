ScrollSide
=========

ScrollSide aims to prevent the problem presented by mousewheel scrolling on horizontal pages by hijacking the mousewheel event. When you’ve included ScrollSide into your site, your user can use the mouse wheel to scroll up to go left and down to move right.

How to Use
----------

ScrollSide should be initialized when you'd like the mousewheel event to be highjacked -- most likely as soon as possible.
	
### Javascript
	var ss = new ScrollSide(document.body);

For specific usage and options, please read the documentation or visit [http://davidwalsh.name/js/scrollside](http://davidwalsh.name/js/scrollside)