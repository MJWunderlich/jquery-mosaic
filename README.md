# jquery-mosaic
See documentation and working examples here http://jquery-mosaic.tin.cat

A jQuery plugin by Tin.cat that builds responsive mosaics of images or any other content fitted to match heights in multiple rows while maintaining aspect ratios.

Works wonderfully with images by creating a visually ordered and pleasant mosaic (much like mosaics on Flickr, 500px and Google+) without gaps between elements, but at the same time respecting aspect ratios. Reacts to window resizes and adapts responsively to any screen size.

### Version history
* **v0.15** Added the ability to pass parameters as html data-* attributes. Solved floating point width bug for compatibility with jQuery versions < 3. Thanks to [@BenTalagan](https://github.com/BenTalagan).
* **v0.14** New maxRowHeightPolicy 'tail' that renders items respecting their aspect ratio without surpassing the specified maxRowHeight, resulting in a last row that might not completely fit the screen horizontally, suggested by [@borekl](https://github.com/borekl) and [@nzjrs](https://github.com/nzjrs).
* **v0.13** New outerMargin and innerGap parameters.

### Compatibility
* Requires at least jQuery version 3.3.0
* Tested successfully on Safari 11.1, Chrome 65.0.3325.181 and Firefox 59.0.2

### For programmers and contributors
* Feedback on browsers / versions tested would be greatly appreciated!
* Minified versions are generated using uglifyjs (https://github.com/mishoo/UglifyJS) and cleancss (https://github.com/jakubpawlowicz/clean-css) with the options below, but feel free to use your own solution.
```
uglifyjs jquery.mosaic.js -c -m -o jquery.mosaic.min.js
cleancss jquery.mosaic.css -e --s0 -o jquery.mosaic.min.css
```

Here's a bonus working site using jQuery mosaic: https://litmind.com

### License
jQuery Mosaic is released under the MIT License, meaning you can do with it whatever you want, even for commercial and obscure purposes. A credit somewhere would be appreciated, though!

### Please
Please don't use jQuery Mosaic to show photos of animal abuse. Seriously.
