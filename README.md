# externalify

Browserify transform that lets you require external modules from any function that follows the require API.

Much like the `external` option to Browserify, but lets you specify a custom name for the `require` function to avoid creating a global `require` symbol.

Basically, it just runs `replace-require-functions`. See the [docs of that package](https://github.com/meteor/replace-require-functions) for examples.

## Installation

```sh
npm install exposify
```

## License

MIT
