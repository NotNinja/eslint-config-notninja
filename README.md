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

This will extend the ECMAScript 5 configuration by default, but you can extend other ECMAScript versions as well. You
also have the option of using either the script (i.e. normal) or ECMAScript modules (e.g `import foo from 'foo'`) source
type for any version, if desired.

| ECMAScript Version | Script           | ECMAScript Module |
| ------------------ | ---------------- | ----------------- |
| Default (5)        | `"notninja"`     | `"notninja/esm"`  |
| 5                  | `"notninja/es5"` | `"notninja/esm5"` |
| 6 (2015)           | `"notninja/es6"` | `"notninja/esm6"` |
| 7 (2016)           | `"notninja/es7"` | `"notninja/esm7"` |
| 8 (2017)           | `"notninja/es8"` | `"notninja/esm8"` |
| 9 (2018)           | `"notninja/es9"` | `"notninja/esm9"` |

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
