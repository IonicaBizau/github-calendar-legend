
# github-calendar-legend [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![Version](https://img.shields.io/npm/v/github-calendar-legend.svg)](https://www.npmjs.com/package/github-calendar-legend) [![Downloads](https://img.shields.io/npm/dt/github-calendar-legend.svg)](https://www.npmjs.com/package/github-calendar-legend) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> The GitHub contributions calendar colors.

## :cloud: Installation

```sh
$ npm i --save github-calendar-legend
```


## :clipboard: Example



```js
const legend = require("github-calendar-legend");

console.log(legend);
// => [ "#eee", "#d6e685", "#8cc665", "#44a340", "#1e6823" ]

console.log(legend.indexOf("#eee"));
// => 0

console.log(legend[4]);
// => "#1e6823"
```

## :memo: Documentation


### exports



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`github-calendar-parser`](https://github.com/IonicaBizau/github-calendar-parser#readme)—Parses the GitHub contributions calendar SVG code into JSON.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
