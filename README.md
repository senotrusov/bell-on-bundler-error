> Please see also [bell-on-bundler-error-plugin](https://github.com/senotrusov/bell-on-bundler-error-plugin) – the same plugin with less minimalistic API.

# Bell on bundler error

Notification on [webpack module bundler](http://webpack.github.io/) build errors by writing bell character to stderr output

## Usage

Add the plugin to the config:

```javascript
{
plugins: [
  require('bell-on-bundler-error')
  ]
}
```

## Installation

Install with the [npm package manager](https://github.com/npm/npm):

```
npm install --save-dev bell-on-bundler-error
```

## License
[MIT](LICENSE)
