This module provides a jCarousel slideshow option for the views_slideshow module.

To use this, follow these steps:

1) Download and extract the following modules and their dependencies to the sites/all/modules (or your team's equivalent)
    views_slideshow_jcarousel
    views_slideshow
    views

2) Download and extract the jCarousel library to libraries folder of drupal root. The source code can be found here:
   https://github.com/jsor/jcarousel/releases

   the folder name you create for this will need to be "jcarousel". the full path should be: libraries/jcarousel

   and when you are done, the following path will need to be available: sites/all/libraries/jcarousel/dist

3) enable the views_slideshow_jcarousel module from http://example.com/admin/modules

4) create or edit a view. Under the Format heading, click "format" and select "slideshow". You should now be able to select and configure your jcarousel slideshow.

    Pager options are on this configuration screen, not under views "pager settings". To decide where you want your pager to go,
    you can tick the pager widget checkbox beneath the area you wish to show it. your choices are "top" or "bottom" of carousel.
