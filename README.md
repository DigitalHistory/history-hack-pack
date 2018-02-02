# History Hack Pack

[![apm](https://img.shields.io/apm/v/history-hack-pack.svg?style=flat-square)](https://atom.io/packages/history-hack-pack)
[![apm](https://img.shields.io/apm/dm/history-hack-pack.svg?style=flat-square)](https://atom.io/packages/history-hack-pack)

A meta-package for learning front-end developmeing in Digital History courses at University of Toronto

## Installation

### apm

Install `history-hack-pack` from Atom's [Package Manager](http://flight-manual.atom.io/using-atom/sections/atom-packages/) or the command-line equivalent:

`$ apm install history-hack-pack`

### Using Git **FIXURL**


**NOT RECOMMENDED FOR STUDENTS!** 

Change to your Atom packages directory:

```bash
# Windows
$ cd %USERPROFILE%\.atom\packages

# Linux & macOS
$ cd ~/.atom/packages/
```

Clone repository as `sublime`:

```bash
$ git clone https://github.com/idleberg/atom-sublime sublime
```

Inside the cloned directory, install Node dependencies:

```bash
$ yarn || npm install
```

### Dependencies

This package makes use of [atom-package-deps](https://github.com/steelbrain/package-deps) to automatically install the following packages:
* [`teletype`](https:/atom.io/packages/teletype) - Edit files together on different computers
* [`atom-js-console`](https:/atom.io/packages/atom-js-console) - open a console and run javascript code directly (for experiments)
* [`atom-runner`](https://atom.io/packages/atom-runner) – run javscript files directly inside Atom (as a ninitial check of your code)
* [`atom-html-preview`](https:/atom.io/packages/atom-html-preview) - Preview html files from within Atom
* [`atom-html-preview`](https:/atom.io/packages/markdown-preview-enhanced) - Preview markdown files from within Atom
* [`git-plus`](https:/atom.io/packages/git-plus) - additional git commands inside Atom
* [`linter`](https:/atom.io/packages/linter) - framework for syntax checking of files
* [`linter-jshint`](https:/atom.io/packages/linter-jshint) - check javascript syntax
* [`linter-htmlhint`](https:/atom.io/packages/linter-htmlhint) - check html syntax
* [`linter-markdown`](https:/atom.io/packages/linter-markdown) - check markdown syntax
* [`auto-update-plus`](https://atom.io/packages/auto-update-plus) – Automatically update packages
* [`autoclose-html`](https://atom.io/packages/autoclose-html) – Autoclose html tags
* [`linter-spell`](https://atom.io/packages/linter-spell) -- spell-chekcing for markdown files (and also HTML & Javascript with the provided additional plugins)

To disable individual packages, go to the Atom settings.

## Contribute

Just getting started with this, so please contribute your ideas if possible

## License

This work is licensed under the [The MIT License](LICENSE.md).
