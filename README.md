Swiper-Scrollbar
================

Scrollbar plugin for Swiper

Scrollbar is the ultra small (about 1Kb minified and gzipped) and free JavaScript plugin for iDangero.us Swiper 1.7+ that adds fully customizable scrollbars to your Swiper slider (or app).

Demos and usage at http://www.idangero.us/sliders/swiper/plugins/scrollbar.php

Build
-----

This project uses `grunt` to build a dist version.

First you need to have `grunt-cli` which you should install globally.
```
$ npm install -g grunt-cli

```

Then install all dependencies,

```
$ npm install
$ grunt
```

The results is available in `dist` folder.

Build demos
-----------

To update demos dependencies you will need to do this first,
```
$ grunt demo
$ cd demos
$ bower install
```

Then you can open demos page in a browser.
You can use `npm` `serve` module which will create a temporary local server, that will help you watch the demos with no setup overhead.

If you don't have already `serve` module installed, the recommanded way is to install it globally:
```
$ npm install -g serve
```

Then launch the temporary web server on any port you want, default being 3000, and give the demo path as the root directory.

If you want to launch on port 5000, being in `./demos` folder, type this:
```
$ serve . -p 5000

```

or being in the root folder:
```
$ serve ./demos/ -p 5000
```

License
-------
GPL & MIT
