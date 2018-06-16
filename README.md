# sucrase-standalone

## Sucrase for ES5

This is a standalone version of
[Sucrase](https://github.com/alangpierce/sucrase) which runs in ES5
environments, such as browsers, old Node.js or Nashorn.

It is built using [Parcel](https://github.com/parcel-bundler/parcel) with
[core-js](https://github.com/zloirock/core-js)
to make it work in non ES6 environments.

It exports the same methods as
[sucrase/src/index.ts](https://github.com/alangpierce/sucrase/blob/master/src/index.ts)
but it also creates an sucrase object on the `global` (`window`).

## Usage

Include `dist/sucrase.min.js` in your app.
