*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/is-empty](http://github.com/ianstormtaylor/is-empty). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-is-empty`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# is-empty

  Check whether a value is empty.

## Installation
  
```
$ component install ianstormtaylor/is-empty
```
```
$ npm install is-empty
```

## Example

```js
var empty = require('is-empty');

empty([]);              // true
empty({});              // true
empty('');              // true
empty(0);               // true
empty(function(){});    // true
empty(null);            // true
empty(undefined);       // true

empty(['a', 'b']);      // false
empty({ a: 'b' });      // false
empty('string');        // false
empty(42);              // false
empty(function(a,b){}); // false
```

## API

### isEmpty(value)

  Check whether `value` is empty.

## License

  MIT
