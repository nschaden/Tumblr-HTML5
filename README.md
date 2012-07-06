# Bare Tumblr

A simple, semantically clean HTML5 based base theme for Tumblr.

Version 0.7 (beta)
Original Author: Nick Schaden
http://nickschaden.com

## Core features

* HTML structure based on the [HTML5 Boilerplate v3](http://html5boilerplate.com).
* Aggressive usage of new semantic html5 elements.
* References the hNews microformat specification when possible.
* Bare-bones, core theme intended as starting point for a theme designer.

## Introduction

Tumblr is great, but when you're interested in rolling your own theme, taking an existing one and wading through the extra cruft isn't usually that fun. Instead, I wanted a very clean, stripped theme to which I could add my own styling and javascript, based off of strong HTML5 fundamentals. So I went ahead and created a few very basic, self contained "themes" for use.

## Installation/structure

Start by [downloading](https://github.com/nschaden/Tumblr-HTML5/zipball/master) the package. There are three completed files to begin work off of:

* *index_base.html*. This is the most bare of bare Tumblr themes. If you were to paste this in as a Tumblr's blog's theme, the page would appear effecively broken, as there's no styling here except for what comes out of the box in normalize.css and a few tweaks as provided by the HTML5 Boilerplate default set. However, if you're really looking to roll your own styling, especially for something that breaks away from a "traditional" single column, text heavy post blog, it's worth starting here.

* *index_corestying.html*. This is the base bare Tumblr theme with a few basic styling added. There's some extra font spacing and 
typography based on the golden section ratio, derived heavily from Tim Brown's [Modular Scale](http://modularscale.com/). There's also basic spacing for posts, formating for imagery, and the like. For those who are keeping to a more traditional or generalized type of Tumblr theme, start from here.

* *index_corestying_sidebar.html*. Very similar to the corestying.html file, with the addition of a very simple right aligned sidebar. If you're going for more of a two column format, I'd recommend starting from this file.

I've also placed a minified copy of Modernizr in the js directory, as all three files refer to a copy of it. There's also a boilerplate-base.css, both minified and unminified, that's placed in a css subdirectory for reference. Again, all three files refer to a previously uploaded copy of the minified version.

## Additional credits

Work here heavily relies on previous work done by the great team over at [HTML5 Boilerplate](http://html5boilerplate.com). Additional help on how to properly write friendly to the hNews microformat specification came from article publishing guidlines over at [Readability](http://www.readability.com/publishers/guidelines). Checks were also made to Mark Pilgrim's [Dive Into HTML5](http://diveintohtml5.ep.io/index.html) for proper semantic usage of some of the new HTMl5 tags.

&copy; 2012 Nick Schaden
