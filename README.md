Modified version of WP Family Tree
==================================

This is a modified version of [WP Family Tree plugin](https://wordpress.org/plugins/wp-family-tree/) (version 1.0.5) by the_arv.

These are the changes from the original plugin:

* New - Added schema.org microdata for person to the single family member pages, and on the family members directory list page. Person properties include name, birth date, death date, parent, children, sibling, and image.

* Tweak - Added spaces between names and dates in tables for better description snippets in search results. Otherwise, without these spaces, if you use the excerpt for the description meta tag, the [names and dates run together](http://isabelcastillo.com/add-spaces-wp-family-tree).

* Fix - Removed PHP error notice for deprecated use of User Levels instead of capabilites.

* Fix - Removed several other PHP warnings.