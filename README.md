# TEXT ALIGN

  Mobile-first text-align classes.
  Set the desired text-align on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install text-align.css --save-dev
```
or download the css on github and include in your project.

## File Size

| File                 | Size |
| -------------------- | ----:|
| gzipped & minified   | 155B |
| text-align.min.css   | 407B |
| text-align.css       | 777B |

## The Code
```
/*

  Text Align

*/

.tl  { text-align: left; }
.tr  { text-align: right; }
.tc  { text-align: center; }

@media screen and (min-width: 48em) {
  .tl-ns  { text-align: left; }
  .tr-ns  { text-align: right; }
  .tc-ns  { text-align: center; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .tl-m  { text-align: left; }
  .tr-m  { text-align: right; }
  .tc-m  { text-align: center; }
}

@media screen and (min-width: 64em)  {
  .tl-l  { text-align: left; }
  .tr-l  { text-align: right; }
  .tc-l  { text-align: center; }
}
```
# License

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

