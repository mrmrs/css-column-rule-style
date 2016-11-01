# css-column-rule-style 1.0.6

Css module of single purpose classes for column rule style

#### Stats

446 | 44 | 132
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-rule-style
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-rule-style
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-rule-style.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-rule-style";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-column-rule-style@1.0.6/css/css-column-rule-style.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-rule-style">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN RULE STYLE
*/
.crs-n { -webkit-column-rule-style: none; -moz-column-rule-style: none; column-rule-style: none; }
.crs-hid { -webkit-column-rule-style: hidden; -moz-column-rule-style: hidden; column-rule-style: hidden; }
.crs-dot { -webkit-column-rule-style: dotted; -moz-column-rule-style: dotted; column-rule-style: dotted; }
.crs-dash { -webkit-column-rule-style: dashed; -moz-column-rule-style: dashed; column-rule-style: dashed; }
.crs-solid { -webkit-column-rule-style: solid; -moz-column-rule-style: solid; column-rule-style: solid; }
.crs-double { -webkit-column-rule-style: double; -moz-column-rule-style: double; column-rule-style: double; }
.crs-groove { -webkit-column-rule-style: groove; -moz-column-rule-style: groove; column-rule-style: groove; }
.crs-ridge { -webkit-column-rule-style: ridge; -moz-column-rule-style: ridge; column-rule-style: ridge; }
.crs-inset { -webkit-column-rule-style: inset; -moz-column-rule-style: inset; column-rule-style: inset; }
.crs-outset { -webkit-column-rule-style: outset; -moz-column-rule-style: outset; column-rule-style: outset; }
.crs-i { -webkit-column-rule-style: inherit; -moz-column-rule-style: inherit; column-rule-style: inherit; }
@media screen and (min-width: 48em) {
 .crs-n-ns { -webkit-column-rule-style: none; -moz-column-rule-style: none; column-rule-style: none; }
 .crs-hid-ns { -webkit-column-rule-style: hidden; -moz-column-rule-style: hidden; column-rule-style: hidden; }
 .crs-dot-ns { -webkit-column-rule-style: dotted; -moz-column-rule-style: dotted; column-rule-style: dotted; }
 .crs-dash-ns { -webkit-column-rule-style: dashed; -moz-column-rule-style: dashed; column-rule-style: dashed; }
 .crs-solid-ns { -webkit-column-rule-style: solid; -moz-column-rule-style: solid; column-rule-style: solid; }
 .crs-double-ns { -webkit-column-rule-style: double; -moz-column-rule-style: double; column-rule-style: double; }
 .crs-groove-ns { -webkit-column-rule-style: groove; -moz-column-rule-style: groove; column-rule-style: groove; }
 .crs-ridge-ns { -webkit-column-rule-style: ridge; -moz-column-rule-style: ridge; column-rule-style: ridge; }
 .crs-inset-ns { -webkit-column-rule-style: inset; -moz-column-rule-style: inset; column-rule-style: inset; }
 .crs-outset-ns { -webkit-column-rule-style: outset; -moz-column-rule-style: outset; column-rule-style: outset; }
 .crs-i-ns { -webkit-column-rule-style: inherit; -moz-column-rule-style: inherit; column-rule-style: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .crs-n-m { -webkit-column-rule-style: none; -moz-column-rule-style: none; column-rule-style: none; }
 .crs-hid-m { -webkit-column-rule-style: hidden; -moz-column-rule-style: hidden; column-rule-style: hidden; }
 .crs-dot-m { -webkit-column-rule-style: dotted; -moz-column-rule-style: dotted; column-rule-style: dotted; }
 .crs-dash-m { -webkit-column-rule-style: dashed; -moz-column-rule-style: dashed; column-rule-style: dashed; }
 .crs-solid-m { -webkit-column-rule-style: solid; -moz-column-rule-style: solid; column-rule-style: solid; }
 .crs-double-m { -webkit-column-rule-style: double; -moz-column-rule-style: double; column-rule-style: double; }
 .crs-groove-m { -webkit-column-rule-style: groove; -moz-column-rule-style: groove; column-rule-style: groove; }
 .crs-ridge-m { -webkit-column-rule-style: ridge; -moz-column-rule-style: ridge; column-rule-style: ridge; }
 .crs-inset-m { -webkit-column-rule-style: inset; -moz-column-rule-style: inset; column-rule-style: inset; }
 .crs-outset-m { -webkit-column-rule-style: outset; -moz-column-rule-style: outset; column-rule-style: outset; }
 .crs-i-m { -webkit-column-rule-style: inherit; -moz-column-rule-style: inherit; column-rule-style: inherit; }
}
@media screen and (min-width: 64em) {
 .crs-n-l { -webkit-column-rule-style: none; -moz-column-rule-style: none; column-rule-style: none; }
 .crs-hid-l { -webkit-column-rule-style: hidden; -moz-column-rule-style: hidden; column-rule-style: hidden; }
 .crs-dot-l { -webkit-column-rule-style: dotted; -moz-column-rule-style: dotted; column-rule-style: dotted; }
 .crs-dash-l { -webkit-column-rule-style: dashed; -moz-column-rule-style: dashed; column-rule-style: dashed; }
 .crs-solid-l { -webkit-column-rule-style: solid; -moz-column-rule-style: solid; column-rule-style: solid; }
 .crs-double-l { -webkit-column-rule-style: double; -moz-column-rule-style: double; column-rule-style: double; }
 .crs-groove-l { -webkit-column-rule-style: groove; -moz-column-rule-style: groove; column-rule-style: groove; }
 .crs-ridge-l { -webkit-column-rule-style: ridge; -moz-column-rule-style: ridge; column-rule-style: ridge; }
 .crs-inset-l { -webkit-column-rule-style: inset; -moz-column-rule-style: inset; column-rule-style: inset; }
 .crs-outset-l { -webkit-column-rule-style: outset; -moz-column-rule-style: outset; column-rule-style: outset; }
 .crs-i-l { -webkit-column-rule-style: inherit; -moz-column-rule-style: inherit; column-rule-style: inherit; }
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

