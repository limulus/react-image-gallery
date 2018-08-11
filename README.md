React Carousel Image Gallery Fork
===

This is a fork of [react-image-gallery](http://www.npmjs.com/package/react-image-gallery). You probably want the real thing, but if you are making a gallery with a lot of images, this fork will avoid rendering content for completely offscreen slides when `lazyLoad` is on. This helps prevents an out-of-memory crash on iOS.

See the changes in my fork’s [fix-ios-safari-oom branch](https://github.com/xiaolin/react-image-gallery/compare/master...limulus:fix-ios-safari-oom).