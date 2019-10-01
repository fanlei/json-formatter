# jf: JSON Formatter
Command-line tool to pretty-print JSON string for human readability by PHP.

## Requirements

PHP needs to be a minimum version of PHP 7.0.0.

## Installation

Globally by Composer

```shell
$ composer global require fanlei/json-formatter
```

## Usage

### In command-line:

Format file `data.json` and output to screen:
```shell
$ jf data.json
```
Format file `data.json` and save to another file `data_formatted.json`:
```shell
$ jf data.json > data_formatted.json
```
    
### In VIM

Format current file:
```VIML
:%!jf %
```

or add a keymap in `vimrc`:
```VIML
nnoremap <Leader>jf :%!jf %<cr>
```