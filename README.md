# CSS WORD SPACING

  Mobile-first classes for css-word-spacing.
  Set the desired css-word-spacing on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-word-spacing
```
View on [npm](https://www.npmjs.org/package/css-word-spacing)


## File Size

637B word-spacing.css
455B word-spacing.min.css
162B minified and gzipped

## The Code
```
.wsn { word-spacing: normal; }
.ws1 { word-spacing: 0.3em; }
.ws2 { word-spacing: -0.43em; } /* For eliminating space between inline-block elements */

@media screen and (min-width: 48em) {
  .wsn-ns { word-spacing: normal; }
  .ws1-ns { word-spacing: 0.3em; }
  .ws2-ns { word-spacing: -0.43em; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .wsn-m { word-spacing: normal; }
  .ws1-m { word-spacing: 0.3em; }
  .ws2-m { word-spacing: -0.43em; }
}

@media screen and (min-width: 64em)  {
  .wsn-l { word-spacing: normal; }
  .ws1-l { word-spacing: 0.3em; }
  .ws2-l { word-spacing: -0.43em; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

