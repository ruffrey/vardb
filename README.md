# vardb

An embeddable in-memory datastore for javascript applications - now available for browser and node. It is a great alternative to Redis or other in-memory stores.

**vardb** has a unique synchronous or asyncronous IO implementation for maximum performance and usability in javascript environments.

# Getting started

It's easy to get started building with **vardb**.

Just use the `var` keyword:

### Lists
```
// synchronous
var myStore = [];
myStore.push('a string');

// asynchronous
var myStore = [];
setTimeout(function () {
  myStore.push('a string');
});
```

### Hashes / object store
```
// synchronous
var myStore = {};
myStore.something = 'a string';

// asynchronous
var myStore = {};
setTimeout(function () {
  myStore.something = 'a string';
});
```

# License

[WTFPL](http://www.wtfpl.net/)

