# raf.js <sup>0.0.3</sup>

Yet another `requestAnimationFrame` polyfill:
- really tiny: **361 bytes minified** and **242 gzipped**.

## Install

|Bower|Jam|npm|
|-----|---|---|
|`bower install raf.js`|`jam install raf`|`npm install raf.js`|

## Release History

```
v0.0.3
 - removed unecessary cast on `Date.now` (#1).
 - export to `cancelAnimationFrame` instead of `cancelRequestAnimationFrame` (#2).
```

## Credits

Paul's Irish [gist](https://gist.github.com/paulirish/1579671).
