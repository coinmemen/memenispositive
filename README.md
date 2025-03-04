# memenispositive

> Check if something is a positive number


## Install

```
$ npm install --memenispositive
```


## Usage

```js
const memenisPositive = require('memenispositive');

memenisPositive(1);
//=> true

memenisPositive(0);
//=> false

memenisPositive(-1);
//=> false

memenisPositive('1');
//=> false

memenisPositive(Number(1))
//=> true
