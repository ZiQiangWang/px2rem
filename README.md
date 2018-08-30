# px2rem-more

px2rem-more is based on the work of [px2rem](https://github.com/songsiqi/px2rem) ，add **keepFontSize** option, which will not convert **font-size** to rem by default. You can set keepFontSize=false to disable the feature.

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Downloads][downloads-image]][downloads-url]

[npm-image]: https://img.shields.io/npm/v/px2rem-more.svg?style=flat-square
[npm-url]: https://npmjs.org/package/px2rem-more
[travis-image]: https://www.travis-ci.org/ZiQiangWang/px2rem.svg?style=flat-square
[travis-url]: https://www.travis-ci.org/ZiQiangWang/px2rem
[coveralls-image]: https://img.shields.io/coveralls/ZiQiangWang/px2rem.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/ZiQiangWang/px2rem
[downloads-image]: http://img.shields.io/npm/dm/px2rem-more.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/px2rem-more

### Install

```
npm install -g px2rem-more
```

### Usage

Refer to [px2rem](https://github.com/songsiqi/px2rem) for usage

### CLI tool

```
$ px2rem -o build src/*.css
```

```
  Usage: px2rem [options] <file...>

  Options:

    -h, --help                      output usage information
    -V, --version                   output the version number
    -u, --remUnit [value]           set `rem` unit value (default: 75)
    -x, --threeVersion [value]      whether to generate @1x, @2x and @3x version stylesheet (default: false)
    -r, --remVersion [value]        whether to generate rem version stylesheet (default: true)
    -b, --baseDpr [value]           set base device pixel ratio (default: 2)
    -p, --remPrecision [value]      set rem value precision (default: 6)
    -o, --output [path]             the output file dirname
    -f, --keepFontSize [value]      whether to keep font size (default true)')
```

To disable keepFontSize，

```
$ px2rem -o build src/*.css -f false
```



