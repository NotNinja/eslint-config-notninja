# !ninja ESlint Configuration

[eslint-config-notninja](https://github.com/NotNinja/eslint-config-notninja) contains standard ESLint configurations for
!ninja packages.

[![License](https://img.shields.io/npm/l/eslint-config-notninja.svg?style=flat-square)](https://github.com/NotNinja/eslint-config-notninja/blob/master/LICENSE.md)
[![Release](https://img.shields.io/npm/v/eslint-config-notninja.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-notninja)

* [Install](#install)
* [Configuration](#configuration)
* [Bugs](#bugs)
* [Contributors](#contributors)
* [License](#license)

## Install

Install using `npm`:

``` bash
$ npm install --save-dev eslint-config-notninja
```

You'll need to have at least [Node.js](https://nodejs.org) installed.

## Configuration

Create an ESLint configuration file within your package that extends this configuration:

``` json
{
  "extends": "notninja",
  ...
}
```

This will import the ECMAScript 5 configuration by default. This can also be done by extending `"notninja/es5"`. For
ECMAScript 6 packages, please extend `"notninja/es6"` instead.

## Bugs

If you have any problems or would like to see changes currently in development you can do so
[here](https://github.com/NotNinja/eslint-config-notninja/issues).

## Contributors

If you want to contribute, you're a legend! Information on how you can do so can be found in
[CONTRIBUTING.md](https://github.com/NotNinja/eslint-config-notninja/blob/master/CONTRIBUTING.md). We want your
suggestions and pull requests!

A list of contributors can be found in
[AUTHORS.md](https://github.com/NotNinja/eslint-config-notninja/blob/master/AUTHORS.md).

## License

See [LICENSE.md](https://github.com/NotNinja/eslint-config-notninja/raw/master/LICENSE.md) for more information on our
MIT license.

[![Copyright !ninja](https://cdn.rawgit.com/NotNinja/branding/master/assets/copyright/base/not-ninja-copyright-186x25.png)](https://not.ninja)
