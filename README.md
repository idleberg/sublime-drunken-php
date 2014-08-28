# Drunken PHP for Sublime Text [![Build Status](https://secure.travis-ci.org/idleberg/Drunken-PHP.svg?branch=branch)](http://travis-ci.org/idleberg/Drunken-PHP)

## Description

PHP is [often](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/) [criticized](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/) for having an inconsistent syntax and this is exactly what *Drunken PHP* aims at. It's a set of alternative command completions, including aliases for ill-formed syntax. Read the section below for examples.

**Note:** More recent versions of Sublime Text 3 received a much improved fuzzy completion. Nevertheless, I still believe that this package makes for a good companion to your standard PHP completions. However, I'm undecided about the future of this project, it's clearly far from being complete. Should you be interested in helping out, feel free to submit a pull request.

## Aliases

You can tell apart *Drunken PHP* from proper syntax from the `%`-prefix displayed in the command completion window.

### Prince Versions

Named after the Prince Emulator in Douglas Coupland's [Microserfs](http://www.wired.com/wired/archive/2.01/microserfs.html), you can substitute any `to` with the number `2` and vice versa

Examples:

* **`bin2hex`** = `bintohex` = `bin_to_hex`
* **`cal_to_jd`** = `cal2jd` = `caltojd`.

### Spacing

Enables you to type commands with or without spacing

Examples:

* **`get_html_translation_table`** = `gethtmltranslationtable`
* **`getimagesizefromstring`** = `get_image_size_from_string`

### Synonyms

Makes some native syntax more descriptive

Examples:

* **`asin`** = `arc_sin` = `arcsin`
* **`asort`** = `array_sort`
* **`bzcompress`** = `bzip_compress`

### Word Order

The order of noun and verb is reversible

Examples:

* **`ini_get`** = `get_ini`
* **`get_class`** = `class_get`

## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.