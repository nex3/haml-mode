# haml-mode for Emacs

`haml-mode` is an Emacs major mode for use with
[HAML](http://haml.info/) source files.

It provides syntax highlighting and support for syntax-aware
indentation.

Support for syntax checking via flymake is available separately: see
[flymake-haml](https://github.com/purcell/flymake-haml).

## Installation

### Via ELPA (recommended)

If you're an Emacs 24 user or you have a recent version of
`package.el` you can install `haml-mode` from the
[MELPA](http://melpa.milkbox.net) or
[Marmalade](http://marmalade-repo.org) package repositories.

### Manually

Ensure `haml-mode.el` is in a directory on your load-path, and
add the following to your `~/.emacs` or `~/.emacs.d/init.el`:

``` lisp
(require 'haml-mode)
```

You will also need to ensure `ruby-mode` is installed: the version in
Emacs 24 is sufficient.

## Optional functionality

Certain nested `:filter` blocks are syntax-highlighted if additional
libraries are available. Emacs 24's `js` library will be used for
`:javascript` blocks, while `markdown-mode` and `textile-mode` will be
used for `:markdown` and `:textile` blocks respectively.


## About

Author: Nathan Weizenbaum

Maintainer: [Steve Purcell](https://github.com/purcell) <steve at sanityinc dot com>

Homepage: https://github.com/nex3/haml-mode
