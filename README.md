# rxportal

RxPortal Template


Just a simple placeholder template for RxPortal until it
launches. Includes a search bar and a cool slideshow background (more on both below).

Demo images courtesy of Unsplash, a collection of CC0 (public domain) images
you can use for pretty much whatever.

Search Form:

	The search form won't actually do anything (other than report back with a "search successful" message)
	until you tie it to your own hosted solution.
	In either case, there are two ways to go:


Slideshow Background:

	This is pretty straightforward, but there are two JS settings you'll want to be aware of
	(found under "Slideshow Background" in assets/js/main.js):

	images

		The list of images to cycle through, given in the following format:

			'url': 'alignment'

		Where 'url' is the image (eg. 'images/foo.jpg', 'http://somewhere.else/foo.jpg'), and
		'alignment' is how the image should be vertically aligned ('top', 'center', or 'bottom').

		Note: Browsers that don't support CSS transitions (like IE<=9) will only see the first image.

	delay

		How long to wait between transitions (in ms). Note that this must be at least twice as long as
		the transition speed itself (currently 3 seconds).


Credits:

	Demo Images:
		Unsplash (unsplash.com)
		Pixabay (pixabay.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		Responsive Tools (github.com/ajlkn/responsive-tools)
