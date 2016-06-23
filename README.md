# GitHub dark syntax theme

[![NPM version](http://img.shields.io/npm/v/github-syntax-dark.svg)](https://www.npmjs.org/package/github-syntax-dark)

> The CSS dark syntax theme for GitHub

## Install

This repository is distributed with [npm][npm]. After [installing npm][install-npm], you can install `github-syntax-dark` with this command.

```
$ npm install --save github-syntax-dark
```

## Usage

Somewhere in your styles import the syntax theme like this.

```css
@import "github-syntax-dark/lib/github-dark.css";
```

## Build

This was generated by the [github-syntax-theme-generator](https://github.com/primer/github-syntax-theme-generator). To rebuild, you will need to follow the instructions there.

## Contributing

For any bugs, fill reports with the [generator](https://github.com/primer/github-syntax-theme-generator/issues). For shipping a new version, run the npm script `npm run ship`. This will

- Update the lib files
- Update the version to match the github-syntax-theme-generator version
- Push to GitHub
- Publish to npm

## Changelog

The [changelog](https://github.com/primer/github-syntax-theme-generator/blob/master/CHANGELOG.md) is kept in the generator repository.

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
