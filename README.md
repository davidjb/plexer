<!--
# This file is automatically generated by a `metapak`
# module. Do not change it elsewhere, changes would
# be overridden.
-->
# plexer
> A stream duplexer embracing Streams 2.0 (for real).

[![NPM version](https://badge.fury.io/js/plexer.svg)](https://npmjs.org/package/plexer)
[![Build status](https://secure.travis-ci.org/nfroidure/plexer.svg)](https://travis-ci.org/nfroidure/plexer)
[![Dependency Status](https://david-dm.org/nfroidure/plexer.svg)](https://david-dm.org/nfroidure/plexer)
[![devDependency Status](https://david-dm.org/nfroidure/plexer/dev-status.svg)](https://david-dm.org/nfroidure/plexer#info=devDependencies)
[![Coverage Status](https://coveralls.io/repos/nfroidure/plexer/badge.svg?branch=master)](https://coveralls.io/r/nfroidure/plexer?branch=master)
[![Code Climate](https://codeclimate.com/github/nfroidure/plexer.svg)](https://codeclimate.com/github/nfroidure/plexer)
[![Dependency Status](https://dependencyci.com/github/nfroidure/plexer/badge)](https://dependencyci.com/github/nfroidure/plexer)


## Usage

### plexer([options,] writable, readable)

#### options
##### options.reemitErrors
Type: `Boolean`
Default value: `true`

Tells the duplexer to reemit given streams errors.

##### options.objectMode
Type: `Boolean`
Default value: `false`

Use if given in streams are in object mode. In this case, the duplexer will
 also be in the object mode.

##### options.*

Plexer inherits of Stream.Duplex, the options are passed to the
 parent constructor so you can use it's options too.

#### writable
Type: `Stream`

Required. Any writable stream.

#### readable
Type: `Stream`

Required. Any readable stream.

### plexer.obj([options], writable, readable)

A shortcut for `plexer({objectMode: true})`.

## Stats

[![NPM](https://nodei.co/npm/plexer.png?downloads=true&stars=true)](https://nodei.co/npm/plexer/)
[![NPM](https://nodei.co/npm-dl/plexer.png)](https://nodei.co/npm/plexer/)

## Contributing
Feel free to pull your code if you agree with publishing it under the MIT license.

# License
[MIT](https://github.com/nfroidure/plexer/blob/master/LICENSE)
