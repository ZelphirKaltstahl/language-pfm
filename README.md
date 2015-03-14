# Pandoc flavored Markdown package [![wercker status](https://app.wercker.com/status/e2bfecae6e8a971093516b3b3ddd4721/s/dist "wercker status")](https://app.wercker.com/project/bykey/e2bfecae6e8a971093516b3b3ddd4721)
![screen shot 2015-03-14 at 15 36 12](https://cloud.githubusercontent.com/assets/2906107/6652065/f9d4048a-ca60-11e4-8c3f-c490c68b6559.png)

Adds syntax highlighting and snippets to [Pandoc flavored Markdown](http://johnmacfarlane.net/pandoc/README.html)
files in Atom. This was forked from [atoms language-gfm](https://github.com/atom/language-gfm). The goal is to maintain compatibility with the **Github Flavored Markdown** package while adding as much pandoc functionality as possible.

In order for `language-pfm` to work you have to disable `language-gfm`.

This package has it's own math highlighting, copied from: [language-latex](https://atom.io/packages/language-latex).

**Supported Pandoc Features**

* Math syntax with inline `$...$` and `\(...\)` and block `$$...$$` and `\[...\]`
* [Definition Lists]
* [Raw HTML] with [inline markdown]
* ... more to come!

[Definition Lists]: http://johnmacfarlane.net/pandoc/README.html#extension-definition_lists
[Raw HTML]: http://johnmacfarlane.net/pandoc/README.html#extension-raw_html
[inline markdown]: http://johnmacfarlane.net/pandoc/README.html#extension-markdown_in_html_blocks

**Works great with other ATOM pandoc related packages**

* [Autocomplete Bibtex] brings citation autocompletion
* [Pen Paper Coffee] is a good looking theme for markdown editing
* [Markdown Preview Plus] is a wonderful markdown preview with Mathjax support, hopefully able to work with pandoc natively soon: [#27]

[Autocomplete Bibtex]: https://atom.io/packages/autocomplete-bibtex

[Pen Paper Coffee]: https://atom.io/packages/pen-paper-coffee-syntax

[Markdown Preview Plus]: https://atom.io/packages/markdown-preview-plus

[#27]: https://github.com/Galadirith/markdown-preview-plus/pull/27
