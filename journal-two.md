I learned how to use jquery to append items to the HTML in one fell swoop and how to use the forEach method instead of using for-loops. How do I feel about it?! Uh.. Great! I do need a little more exposure to the methods though. The lab provided us a chance to experience the use of some traversing and setting methods, and refactoring for-loops. We also used the clone method to save templates for appending additional data in the same context.

pubdate.... is a publication date Outdated

We looked at events and jQuery. Events are the beating heart of any JS App. We use the .on() method for event handlers. Bubbling events work from within the HTML, out. Capturing works out to in.

Example of On Click Event... Tab Based Navigation
$('el').on('click', function() {
	$('el').hide();
	.fadeIn(750);
});
