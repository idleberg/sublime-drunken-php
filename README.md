# Drunken PHP for Sublime Text

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Package Control](https://packagecontrol.herokuapp.com/downloads/Drunken%20PHP.svg?style=flat-square)](https://packagecontrol.io/packages/Drunken%20PHP)
[![Travis](https://img.shields.io/travis/idleberg/Drunken-PHP.svg?style=flat-square)](https://travis-ci.org/idleberg/Drunken-PHP)

## Description

PHP is [often](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/) [criticized](http://tnx.nl/php.html) for having an inconsistent syntax and this is exactly what *Drunken PHP* aims at. It's a set of alternative command completions, including aliases for ill-formed syntax. Read the [Aliases](#aliases) section below for examples.

**Note:** More recent versions of Sublime Text 3 received a much improved fuzzy completion. Nevertheless, I still believe that this package makes for a good companion to your standard PHP completions. However, I'm undecided about the future of this project, it's clearly far from being complete. Should you be interested in helping out, feel free to submit a pull request.

## Installation

### Package Control

1. Make sure you already have [Package Control](https://sublime.wbond.net/installation) installed
2. Choose “*Install Package*” from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type “*Drunken PHP*” and press <kbd>Enter</kbd>

With [auto_upgrade](http://wbond.net/sublime_packages/package_control/settings/) enabled, Package Control will keep all installed packages up-to-date!

### GitHub ###

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/Drunken-PHP.git`

### Manual Installation ###

1. Download the files using the GitHub [.zip](https://github.com/idleberg/Drunken-PHP/archive/master.zip) download option
2. Unzip the files to your Sublime Text `Packages` directory

## Usage

As with all [completions](https://sublime-text-unofficial-documentation.readthedocs.org/en/latest/extensibility/completions.html), type and press `Tab` to complete the command. Press `Tab` again to jump to the next parameter, `Shift+Tab` to jump back. Note there are two jumps available when the parameter defaults to a variable.

## Aliases

You can tell apart *Drunken PHP* from proper syntax from the `%`-prefix displayed in the command completion window. Aliases have been broken up into the following categories:

### Prince Versions

Named after the Prince Emulator in Douglas Coupland's [Microserfs](http://www.wired.com/wired/archive/2.01/microserfs.html), you can substitute any `to` with the number `2` and vice versa.

Examples:

PHP         | Alias
------------|-----------
`bin2hex`   | `bintohex`
`cal_to_jd` | `cal2jd`

### Spacing

Enables you to type commands with or without spacing. Probably obsolete due to fuzzy completions.

Examples:

PHP                          | Alias
-----------------------------|-----------------------------
`get_html_translation_table` | `gethtmltranslationtable`
`getimagesizefromstring`     | `get_image_size_from_string`

### Spelling

Corrects common spelling mistakes.

Examples:

PHP             | Alias
----------------|-----------------------------
`mb_strwidth`   | `mb_strwidht`
`ob_get_length` | `ob_get_lenght`
`phpversion`    | `phpverison`

### Synonyms

Makes some native syntax more descriptive

Examples:

PHP          | Alias
-------------|------------------------
`asin`       | `arc_sin` (or `arcsin`)
`asort`      | `array_sort`
`bzcompress` | `bzip_compress`

### Word Order

The order of noun and verb is reversible

Examples:

PHP           | Alias
--------------|-----------
`ini_get`     | `get_ini`
`get_class`   | `class_get`

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
