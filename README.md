# Random-code.js

Random-code.js is a library for generate random codes

## Installation

```bash
npm install random-code.js
```

## Usage

> Generate Random Code With Default Options (length = 8)

```javascript
const randomCode = require("random-code.js");

console.log(randomCode.generateOne())
```

> Generate Random Code With Custom Length

```javascript
const randomCode = require("random-code.js");

console.log(randomCode.generateOne({
  length: 12
}));
```

> Generate Random Code With Prefix

```javascript
const randomCode = require("random-code.js");

console.log(randomCode.generateOne({
  prefix: "hello-"
}));
```

> Generate Random Code With Postfix

```javascript
const randomCode = require("random-code.js");

console.log(randomCode.generateOne({
  postfix: "-world"
}));
```

> Generate Random Code With Custom Length & Prefix & Postfix

```javascript
const randomCode = require("random-code.js");

console.log(randomCode.generateOne({
  length: 12,
  prefix: "hello-",
  postfix: "-world"
}));
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
