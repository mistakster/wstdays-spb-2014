# From simple to complex

*[Web Standards Days, St. Petersburg, June 2014](http://webstandardsdays.ru/2014/06/28/)*

A mobile phones has almost the same processing power as a computers. But slow and unstable network, small screens imposes significant limitations to they usage. Luke Wroblewski in his book “[Mobile First](http://www.abookapart.com/products/mobile-first)” describes some principles of designing user interaction in such “extreme” conditions. This talk focuses on the implementation of certain principles:

* responsive images and lazy loading;
* dynamic style and script injections;
* optimization of the page rendering;
* building the project.

Also, I explain following topics:

* Why we have started using “Mobile First” approach.
* Why numbers of network requests matter especially for mobile environment.
* How to use `matchMedia` to tracking environment.
* How to implement responsive images using <picture> tag and its polyfills.
* What benefits you can get from external image hosting and CDN.
* How we improved speed of the compilation of styles.
