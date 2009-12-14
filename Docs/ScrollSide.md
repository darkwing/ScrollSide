Class: ScrollSide {#ScrollSide}
=================================

### Implements:

Options, Events


ScrollSide Method: constructor {#ScrollSide:constructor}
-----------------------------------------------------------


### Syntax:

	var ss = new ScrollSide(document.body);

### Arguments:

1. container - (*string*)  The ID of the container which will have its mousewheel event highjacked.
2. options - (**)  The options for the ScrollSide instance.

### Options:

* movement - (*integer*, defaults to 75) - The number of pixels to scroll on each wheel movement.
* reset - (*boolean*, defaults to true) - Sets the container to the {x:0,y:0} position on instantiation.


### Events:

### onScrollUp

* (*function*) Function to execute when the container is scrolled "up".

### Signature

	onScrollUp(fn)
	
### onScrollDown

* (*function*) Function to execute when the container is scrolled "down".

### Signature

	onScrollDown(fn)