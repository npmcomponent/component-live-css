*This repository is a mirror of the [component](http://component.io) module [component/live-css](http://github.com/component/live-css). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-live-css`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# live-css

  CSS changes live as they happen in development.

## Installation

    $ component install --dev component/live-css

## Example

  Simply require and `.start()`:

```js
require('live-css').start();
```

## Testing

```
$ npm install -g serve
$ serve . &
$ http://localhost:3000/demo/
```

## License

  MIT
