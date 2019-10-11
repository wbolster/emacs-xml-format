xml-format.el
=============

This is an Emacs package to make it easy to [reformat](https://github.com/purcell/reformatter.el) XML files using the [xmllint](http://xmlsoft.org/xmllint.html) utility. `xmllint` is is part of [libxml2](http://xmlsoft.org/), and available from most software repositories, e.g. `apt install libxml2-utils` on Debian/Ubuntu.

Installation
------------

Install the [xml-format Melpa package](https://melpa.org/#/xml-format) using `M-x package-install`, or via [use-package](https://github.com/jwiegley/use-package):

``` elisp
(use-package xml-format
  :demand t
  :after nxml-mode)
```

Usage
-----

Use one of these commands via `M-x` or bind them to a key:

- `xml-format-on-save-mode`

  Automatically reformat the buffer on save.

- `xml-format-buffer`

  Reformat the current buffer.

- `xml-format-region`

  Reformat the current region.

Configuration
-------------

This package deliberately has minimal configuration. Use `M-x customize-group RET xml-format` or change these variables in your `init.el`:

- `xml-format-xmllint-executable`
- `xml-format-xmllint-args`

License
-------

BSD-3-clause. Copyright © 2019 wouter bolsterlee.

Credits
-------

wouter bolsterlee. wbolster.

https://github.com/wbolster on github. star my repos. fork them. and so on.

https://twitter.com/wbolster on twitter. follow me. or say hi.
