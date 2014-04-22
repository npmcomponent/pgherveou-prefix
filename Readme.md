*This repository is a mirror of the [component](http://component.io) module [pgherveou/prefix](http://github.com/pgherveou/prefix). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/pgherveou-prefix`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# prefix

  get style prefixed name

## Installation

    $ component install pgherveou/prefix

## API

```js
var prefix = require('prefix');
prefix('transform'); // return prefixed style eg: webkitTransform
prefix('transform', true); // return prefixed dasherized style eg -webkit-transform
```

## License

  MIT
