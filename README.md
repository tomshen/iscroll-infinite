# iScroll Infinite Scrolling

This is a fork of [iScroll](http://iscrolljs.com/)'s infinite scrolling module. From the original repo:

> iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller.
>
> It works on desktop, mobile and smart TV. It has been vigorously optimized for performance and size so to offer the smoothest result on modern and old devices alike.
>
> iScroll does not just *scroll*. It can handle any element that needs to be moved with user interaction. It adds scrolling, zooming, panning, infinite scrolling, parallax scrolling, carousels to your projects and manages to do that in just 4kb. Give it a broom and it will also clean up your office.
>
> Even on platforms where native scrolling is good enough, iScroll adds features that wouldn't be possible otherwise. Specifically:
>
> * Granular control over the scroll position, even during momentum. You can always get and set the x,y coordinates of the scroller.
> * Animation can be customized with user defined easing functions (bounce, elastic, back, ...).
> * You can easily hook to a plethora of custom events (onBeforeScrollStart, onScrollStart, onScroll, onScrollEnd, flick, ...).
> * Out of the box multi-platform support. From older Android devices to the latest iPhone, from Chrome to Internet Explorer.
>
> iScroll integrates a smart caching system that allows to handle of a virtually infinite amount of data using (and reusing) just a bunch of elements.

## Documentation
The majority of the code is for general scrolling. The functions that handle infinite scrolling are:
* `_initInfinite`
* `reorderInfinite`
* `updateContent`
* `updateCache`

See the [JSDoc](http://www.tomshen.me/iscroll-infinite/docs/) for more details.
