# sasslint-config-springernature
[![NPM version](http://img.shields.io/npm/v/%40springernature%2Fsasslint-config.svg)](https://www.npmjs.org/package/%40springernature%2Fsasslint-config)

[Sass Lint](https://github.com/sasstools/sass-lint) shareable config used at Springer Nature

## Requirements

This package requires `sass-lint` version 1.12 or greater.

## Installation

1. Install `sass-lint` to your devDependencies
```
npm install --save-dev sass-lint
```

2. Install this `sasslint-config` to your devDependencies
```
npm install --save-dev @springernature/sasslint-config
```

3. Add the `sasslintConfig` option to your `package.json` file, and point it to the shared `.sass-lint.yml`

```json
{
  "name": "my-project",
  "version": "1.0.0",
  "sasslintConfig": "./node_modules/@springernature/sasslint-config/config/.sass-lint.yml"
}
```

4. Run `sass-lint` without specifiying a config

```
sass-lint './scss/*.scss'
```

## Contributing

This package is used by many active Springer Nature projects. We always welcome issues and pull requests, but we may not always be able to merge your suggestions.

If we decide that we can't merge your PR or act on your issue, it's nothing personal! We love to see new contributors, and we strive to provide a welcoming and inclusive environment.
