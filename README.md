# CSS COLUMN RULE STYLE

  Mobile-first classes for css-column-rule-style.
  Set the desired css-column-rule-style on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-column-rule-style
```
or download the css on github and include in your project.

## File Size


## The Code
```
.crs-n {      column-rule-style: none; }
.crs-hid {    column-rule-style: hidden; }
.crs-dot {    column-rule-style: dotted; }
.crs-dash {   column-rule-style: dashed; }
.crs-solid {  column-rule-style: solid; }
.crs-double { column-rule-style: double; }
.crs-groove { column-rule-style: groove; }
.crs-ridge {  column-rule-style: ridge; }
.crs-inset {  column-rule-style: inset; }
.crs-outset { column-rule-style: outset; }
.crs-i {      column-rule-style: inherit; }

@media screen and (min-width: 48em) {
  .crs-n-ns {      column-rule-style: none; }
  .crs-hid-ns {    column-rule-style: hidden; }
  .crs-dot-ns {    column-rule-style: dotted; }
  .crs-dash-ns {   column-rule-style: dashed; }
  .crs-solid-ns {  column-rule-style: solid; }
  .crs-double-ns { column-rule-style: double; }
  .crs-groove-ns { column-rule-style: groove; }
  .crs-ridge-ns {  column-rule-style: ridge; }
  .crs-inset-ns {  column-rule-style: inset; }
  .crs-outset-ns { column-rule-style: outset; }
  .crs-i-ns {      column-rule-style: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .crs-n-m {      column-rule-style: none; }
  .crs-hid-m {    column-rule-style: hidden; }
  .crs-dot-m {    column-rule-style: dotted; }
  .crs-dash-m {   column-rule-style: dashed; }
  .crs-solid-m {  column-rule-style: solid; }
  .crs-double-m { column-rule-style: double; }
  .crs-groove-m { column-rule-style: groove; }
  .crs-ridge-m {  column-rule-style: ridge; }
  .crs-inset-m {  column-rule-style: inset; }
  .crs-outset-m { column-rule-style: outset; }
  .crs-i-m {      column-rule-style: inherit; }
}

@media screen and (min-width: 64em)  {
  .crs-n-l {      column-rule-style: none; }
  .crs-hid-l {    column-rule-style: hidden; }
  .crs-dot-l {    column-rule-style: dotted; }
  .crs-dash-l {   column-rule-style: dashed; }
  .crs-solid-l {  column-rule-style: solid; }
  .crs-double-l { column-rule-style: double; }
  .crs-groove-l { column-rule-style: groove; }
  .crs-ridge-l {  column-rule-style: ridge; }
  .crs-inset-l {  column-rule-style: inset; }
  .crs-outset-l { column-rule-style: outset; }
  .crs-i-l {      column-rule-style: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

