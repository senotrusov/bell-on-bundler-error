> Please see also [bell-on-bundler-error-plugin](https://github.com/senotrusov/bell-on-bundler-error-plugin) – the same plugin with less minimalistic API.

# Bell on bundler error

Get notification on [webpack module bundler](http://webpack.github.io/) build errors.
On that occasion, a bell character will be written to STDERR output.

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


## Copyright and License

```
Copyright 2015 Stanislav Senotrusov

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


## Contributing

Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.
