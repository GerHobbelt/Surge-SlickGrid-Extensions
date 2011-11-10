About
=====
The Surge SlickGrid Extensions v1.0 provided by the Surge Consulting Group is a set of open-source tools that will make using data grids in your web applications a breeze. The product can be conceptually broken down into the following features:

* A jQuery widget which wraps the open-source SlickGrid tool and gives an API for working with it that is more natural to a jQuery user. This includes the ability to define grid columns in mark-up.
* Various extensions that add some nice bits of functionality to the base widget, including:
  * Use jQuery Templates for Headers, Footers, and formatting columns
  * JSONDataSource object to easily support bottomless scrolling
  * standard set of editors and formatterses and formatter aliases
* A standard set of editors and formatters.
* Utility code in the Surge namespace that is used in implementing the above.

Why Use It?
============
If your application needs a cross-platform, excel-like, javascript grid then the Surge SlickGrid might be for you.

If you already use jQuery UI widgets and would like to interact with the grid in a similar manner, these extensions will allow you to do just that. If you already use jQuery Templates and would like to use them in your grid, Surge SlickGrid offers built-in support. If you would like easy-to-set-up bottomless scrolling, formatter aliases, and facades for commonly used column types, we've got you covered.

And best of all, it's FREE.

Installation
============
As Surge.SlickGrid Extensions is entirely a client-side library just reference the provided javascript and css files as you normally would. [See article on Github.](https://github.com/surgeforward/Surge-SlickGrid-Extensions/wiki/Getting-and-Installing-Surge-SlickGrid-Extensions)

Dependencies
============
Surge SlickGrid Extensions currently has the following dependencies:

* **Required** - Surge SlickGrid will not run without the following
  * [jQuery](http://jquery.com) (not included)
  * [jQuery UI widget factory](http://jqueryui.com/download) (not included)
  * SlickGrid v1.4.3  (included slick.grid.css, slick.grid.js) - SlickGrid v2.0 support is experimental
  * Surge.Core (included surge.core.js)
  * Surge.SlickGrid (included surge.slickGrid.css, surge.slickGrid.js)
* **Optional** - Certain features of Surge SlickGrid will not work without the following
  * [jQuery.event.drag 2.0](http://threedubmedia.com/code/event/drag)
  * [jQuery Templates](http://api.jquery.com/category/plugins/templates/)
  * [jQuery Globalize](http://wiki.jqueryui.com/w/page/39118647/Globalize)
  * [jQuery TimeEntry](http://keith-wood.name/timeEntry.html)

Always check the browser console log for errors that might occur due to missing dependencies.

References
==========
 * [Surge Consulting Group](http://www.surgeforward.com/)
 * [Sign Up for the Surge Mailing List](https://docs.google.com/spreadsheet/viewform?formkey=dG1wN2xSWDVEV0VGQ1YyTTZoWjFaV3c6MQ)
 * [Introductory Tutorial Index](http://blog.surgeforward.com/node/17)
 * [SlickGrid Extensions Demo](http://platformdemo.surgeforward.com/Grid/)
 * [Surge API Reference](http://docs.surgeforward.com/Javascript/files/surge-slickGrid-js.html)
 * [Original SlickGrid Documentation](http://github.com/mleibman/SlickGrid/wiki)