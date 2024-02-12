# scrollspy

# Implement scrollspy directly by IntersectionObserver without *any* external library

The javascript will spy the parent with #main_div id for its daughters with .content class with IntersectionObserver.

Then the links with the associated href with the added or removed with .active class according.

The containing DIV (#menu_div) in the example will be scrolled if necessary so that the active link will be always in view.

Unlike other libraries, if there are more than one elements in view inside the #main_div, *all* these assoicated links will be turned active.
