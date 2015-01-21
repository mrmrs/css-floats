# CSS FLOATS

  Mobile-first classes for css-floats.
  Set the desired css-floats on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-floats
```
View on [npm](https://www.npmjs.org/package/css-floats)


## File Size

598B floats.css
459B floats.min.css
164B minified and gzipped

## The Code
```
.fl { float: left;  display: inline; }
.fr { float: right; display: inline; }
.fn { float: none; }

@media screen and (min-width: 48em) {
  .fl-ns { float: left;  display: inline; }
  .fr-ns { float: right; display: inline; }
  .fn-ns { float: none; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fl-m { float: left;  display: inline; }
  .fr-m { float: right; display: inline; }
  .fn-m { float: none; }
}

@media screen and (min-width: 64em)  {
  .fl-l { float: left;  display: inline; }
  .fr-l { float: right; display: inline; }
  .fn-l { float: none; }
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

