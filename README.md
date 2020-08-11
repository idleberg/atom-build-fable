# build-fable

[![apm](https://img.shields.io/apm/l/build-fable.svg?style=flat-square)](https://atom.io/packages/build-fable)
[![apm](https://img.shields.io/apm/v/build-fable.svg?style=flat-square)](https://atom.io/packages/build-fable)
[![apm](https://img.shields.io/apm/dm/build-fable.svg?style=flat-square)](https://atom.io/packages/build-fable)
[![Travis](https://img.shields.io/travis/idleberg/atom-build-fable.svg?style=flat-square)](https://travis-ci.org/idleberg/atom-build-fable)
[![David](https://img.shields.io/david/idleberg/atom-build-fable.svg?style=flat-square)](https://david-dm.org/idleberg/atom-build-fable)
[![David](https://img.shields.io/david/dev/idleberg/atom-build-fable.svg?style=flat-square)](https://david-dm.org/idleberg/atom-build-fable?type=dev)

[Atom Build](https://atombuild.github.io/) provider for `fable`, transpiles F# into JavaScript.

## Installation

### apm

Install `build-fable` from Atom's [Package Manager](http://flight-manual.atom.io/using-atom/sections/atom-packages/) or the command-line equivalent:

`$ apm install build-fable`

### Using Git

Change to your Atom packages directory:

```bash
# Windows
$ cd %USERPROFILE%\.atom\packages

# Linux & macOS
$ cd ~/.atom/packages/
```

Clone repository as `build-fable`:

```bash
$ git clone https://github.com/idleberg/atom-build-fable build-fable
```

Inside the cloned directory, install Node dependencies:

```bash
$ yarn || npm install
```

## Usage

### Build

Before you can build, select an active target with your preferred build option.

Available targets:

* `Fable` - transpile current file
* `Fable config` - transpile using `fableconfig.json` in the project path
* `Fable [user]` - transpile with custom arguments

### Shortcuts

Here's a reminder of the default shortcuts you can use with this package:

**Select active target**

<kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>T</kbd> or <kbd>F7</kbd>

**Build script**

<kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>B</kbd> or <kbd>F9</kbd>

**Jump to error**

<kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>G</kbd> or <kbd>F4</kbd>

**Toggle build panel**

<kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>V</kbd> or <kbd>F8</kbd>

## License

This work is licensed under the [The MIT License](LICENSE.md).
