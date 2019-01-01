
## Contributing to this site:

 - Publish all site content to content/ as .md files.
 - Talk to Aaron for questions.


## Hints

* See `_includes/header.html` to tweak the navigation bar. The `nav_order` is a custom defined property of each page to determine the order of links on the navigation bar. Any number assigned less than 0 will be hidden. Remaining pages are sorted in increasing order.
* If the footer or any posts are added to the website, then make sure to check for mobile-friendly design. In particular, run `bundle show minima` (the default theme), navigate to the directory, and in the `_sass/minima.scss` file, there are macros and parameters for the base theme. `_sass/minima/_layout.scss` has the actual CSS.
