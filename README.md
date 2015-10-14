workshopper-mocha-boilerplate
==========

> A boilerplate for workshopper modules with Mocha tests and ES6 syntax

[![npm](https://img.shields.io/npm/v/workshopper-mocha-boilerplate.svg?style=flat-square)](https://www.npmjs.com/package/workshopper-mocha-boilerplate) [![Build Status](https://img.shields.io/travis/ThibWeb/workshopper-mocha-boilerplate.svg?style=flat-square)](https://travis-ci.org/ThibWeb/workshopper-mocha-boilerplate) [![dependency Status](https://img.shields.io/david/ThibWeb/workshopper-mocha-boilerplate.svg?style=flat-square)](https://david-dm.org/ThibWeb/workshopper-mocha-boilerplate) [![devDependency Status](https://img.shields.io/david/dev/ThibWeb/workshopper-mocha-boilerplate.svg?style=flat-square)](https://david-dm.org/ThibWeb/workshopper-mocha-boilerplate)

> TODO Screenshot

1. Install [Node.js](http://nodejs.org/)
2. Run `npm install -g workshopper-mocha-boilerplate`
3. Run `workshopper-mocha-boilerplate`
4. **.. profit!**

## Releasing your own workshopper module

```sh
# Install the project
git clone git@github.com:ThibWeb/workshopper-mocha-boilerplate.git
cd workshopper-mocha-boilerplate
npm install
# Make sure it runs
node src/index.js
```

## Contributing

Install the project with:

```sh
git clone git@github.com:ThibWeb/workshopper-mocha-boilerplate.git
cd workshopper-mocha-boilerplate
npm install
npm install -g eslint babel-eslint eslint-config-airbnb
./.githooks/deploy
```

To run the workshopper locally:

```sh
node src/index.js
```

To release a new version:

```sh
npm version minor -m "Release %s"
git push origin master
git push --tags
npm publish
```
