# 0x01. ES6 Promises

## Description💡

One simply does not use async/await without knowing promises!

* Promises (how, why, and what)
* How to use the `then`, `resolve`, `catch` methods
* How to use every method of the Promise object
* Throw / Try
* The await operator
* How to use an `async` function

import getResponseFromAPI from './0-promise';

const response = getResponseFromAPI();
console.log(response instanceof Promise);
