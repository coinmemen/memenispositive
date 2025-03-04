# memenispositive

> Check if something is a positive number


## Install

```
$ npm install --memenispositive
```


## Usage

```js
const memenisPositive = require('memenispositive');

memenisPositive(3);
//=> true

memenisPositive(0);
//=> false

memenisPositive(-2);
//=> false

memenisPositive('4');
//=> false

memenisPositive(Number(5))
//=> true
