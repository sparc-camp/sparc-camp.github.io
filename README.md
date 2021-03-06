
## Getting started

1. Install `ruby`, `gem`, `gcc`, and `make`: https://jekyllrb.com/docs/
2. `gem install jekyll`.
3. `gem install bundler -v "~>1.0"`.
3. `git clone` this repo and add yourself as a contributor to this project on the Github website. 
4. Run `bundle install` in the folder you just cloned down.
5. Edit markdown files in `index.md` and `content/*.md`, and `assets` if you have any images or attachments.
6. Preview your changes with `bundle exec jekyll serve --watch`.
  a. This needs to be run from the base directory.
1. If it looks good to you, add a helpful commit message and push. The website should update automatically within minutes.

[Video overview](https://www.youtube.com/watch?v=r8wH2QCjDpI&feature=youtu.be)

## Contributing to this site:

 - Publish all site content to content/ as .md files.
 - Talk to Aaron for questions.


## Templates, Navigation Bar, Site Layout

* See `_includes/header.html` to tweak the navigation bar. The `nav_order` is a custom defined property of each page to determine the order of links on the navigation bar. Any number assigned less than 0 will be hidden. Remaining pages are sorted in increasing order.
  * To have a page be include in the navbar, its layout must be `page`, have a `nav_order`, and have a `title`.
* If the footer or any posts are added to the website, then make sure to check for mobile-friendly design. In particular, run `bundle show minima` (the default theme), navigate to the directory, and in the `_sass/minima.scss` file, there are macros and parameters for the base theme. `_sass/minima/_layout.scss` has the actual CSS.

