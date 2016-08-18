# css-column-rule-style 0.0.7

Css module of single purpose classes for column rule style

#### Stats

363 | 44 | 44
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-rule-style
```

#### With Git

```
git clone https://github.com/tachyons-css/css-column-rule-style
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-rule-style";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-rule-style">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COLUMN RULE STYLE
*/
.crs-n { column-rule-style: none; }
.crs-hid { column-rule-style: hidden; }
.crs-dot { column-rule-style: dotted; }
.crs-dash { column-rule-style: dashed; }
.crs-solid { column-rule-style: solid; }
.crs-double { column-rule-style: double; }
.crs-groove { column-rule-style: groove; }
.crs-ridge { column-rule-style: ridge; }
.crs-inset { column-rule-style: inset; }
.crs-outset { column-rule-style: outset; }
.crs-i { column-rule-style: inherit; }
@media screen and (min-width: 48em) {
 .crs-n-ns { column-rule-style: none; }
 .crs-hid-ns { column-rule-style: hidden; }
 .crs-dot-ns { column-rule-style: dotted; }
 .crs-dash-ns { column-rule-style: dashed; }
 .crs-solid-ns { column-rule-style: solid; }
 .crs-double-ns { column-rule-style: double; }
 .crs-groove-ns { column-rule-style: groove; }
 .crs-ridge-ns { column-rule-style: ridge; }
 .crs-inset-ns { column-rule-style: inset; }
 .crs-outset-ns { column-rule-style: outset; }
 .crs-i-ns { column-rule-style: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .crs-n-m { column-rule-style: none; }
 .crs-hid-m { column-rule-style: hidden; }
 .crs-dot-m { column-rule-style: dotted; }
 .crs-dash-m { column-rule-style: dashed; }
 .crs-solid-m { column-rule-style: solid; }
 .crs-double-m { column-rule-style: double; }
 .crs-groove-m { column-rule-style: groove; }
 .crs-ridge-m { column-rule-style: ridge; }
 .crs-inset-m { column-rule-style: inset; }
 .crs-outset-m { column-rule-style: outset; }
 .crs-i-m { column-rule-style: inherit; }
}
@media screen and (min-width: 64em) {
 .crs-n-l { column-rule-style: none; }
 .crs-hid-l { column-rule-style: hidden; }
 .crs-dot-l { column-rule-style: dotted; }
 .crs-dash-l { column-rule-style: dashed; }
 .crs-solid-l { column-rule-style: solid; }
 .crs-double-l { column-rule-style: double; }
 .crs-groove-l { column-rule-style: groove; }
 .crs-ridge-l { column-rule-style: ridge; }
 .crs-inset-l { column-rule-style: inset; }
 .crs-outset-l { column-rule-style: outset; }
 .crs-i-l { column-rule-style: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
