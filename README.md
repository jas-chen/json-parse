[![](https://vsmarketplacebadge.apphb.com/version/jaschen.json-parse.svg)](https://marketplace.visualstudio.com/items?itemName=jaschen.json-parse)

# json-parse

Adds syntax highlighting for `JSON.parse(tagged template strings)`.

## Why
> `JSON.parse` approach is much faster compared to the JavaScript object literal, especially for cold loads. \- [The cost of JavaScript in 2019](https://v8.dev/blog/cost-of-javascript-2019)

```js
const data = { foo: 42, bar: 1337 }; // 🐌
const data = JSON.parse('{"foo":42,"bar":1337}'); // 🚀
```

## Demo

Before vs After

![](docs/demo.png)