[![Build Status](https://travis-ci.org/dzhibas/SublimePrettyJson.svg)](https://travis-ci.org/dzhibas/SublimePrettyJson)

Prettify JSON plugin for Sublime Text 2 & 3

## Installation

Install this sublime text package via [Package Control](https://sublime.wbond.net)

## Usage

To prettify JSON, make selection of json and press keys:

- Linux: <kbd>ctrl+alt+j</kbd>
- Windows: <kbd>ctrl+alt+j</kbd>
- OS X: <kbd>cmd+ctrl+j</kbd>

or through Command Palette <kbd>Ctrl+Shift+P</kbd> find "Pretty JSON: Reformat (Pretty Print) JSON"

If selection is empty and configuration entry **use_entire_file_if_no_selection** is true, tries to prettify whole file.

If JSON is not valid it will be displayed in status bar of sublime.

### Compress / Minify JSON

Using Command Palette <kbd>Ctrl+Shift+P</kbd> find "Pretty JSON: Minify (compress) JSON" this will make selection or full buffer as single line JSON which later you can use in command lines or somewhere else

## Default configuration

**use_entire_file_if_no_selection** - true

**indent** - 2

**sort_keys** - false

**ensure_ascii** - false

## Using tabs for indentation

You can change configuration key **indent** to string value "\t" or any other string.

```
"indent" : "\t",
```

Be sure "Indent Using Spaces" is unchecked otherwise you will not see effect and ST2 will convert it back to spaces.

## Thanks

- @the3rdhbtaylor https://github.com/the3rdhbtaylor
- @crcastle https://github.com/crcastle
