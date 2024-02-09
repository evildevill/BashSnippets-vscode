# BashSnippets

BashSnippets is a Visual Studio Code extension that provides a collection of snippets for bash scripting.

## Snippets

Here is a list of all the snippets and their triggers included in this extension:

- `shebang`: Shebang
- `e`: Echo
- `fn`: Function
- `fnd`: Function in a library with definitions of params and exports
- `if`: if block
- `ife`: if else block
- `elif`: elif block
- `until`: until block
- `main`: a main function declaration with passthrough of all parameters passed to the file
- `const`: creates a local readonly variable ie. a constant (this is meant for use within functions only)
- `todo`: creates a local readonly variable ie. a constant
- `array`: Creates an array with two elements
- `forarray`: Creates a loop echoing all variables in an array
- `forindex`: Creates a loop echoing all indexes in a range
- `while`: while loop
- `case`: case statement
- `for`: for loop
- `read`: read input
- `param`: parameter expansion
- `trap`: trap statement
- `here`: here document
- `herestring`: here string
- `herestringdelim`: here string with delimiter
- `heredocdelim`: here document with delimiter
- `heredocEOF`: here document with EOF
- `heredocEOFdelim`: here document with EOF and delimiter
- `herestringEOF`: here string with EOF
- `herestringEOFdelim`: here string with EOF and delimiter
- `herestringdelim`: here string with delimiter
- `export`: Export a variable
- `source`: Source a file
- `alias`: Create an alias
- `test`: Test condition
- `paramsub`: Parameter expansion with substring
- `paramrep`: Parameter expansion with pattern replacement
- `paramlen`: Parameter expansion with length of variable
- `paramdef`: Parameter expansion with default value
- `paramasg`: Parameter expansion with assignment of default value
- `paramerr`: Parameter expansion with error message if variable is unset or null
- `paramsuf`: Parameter expansion with removal of smallest suffix pattern
- `parambig`: Parameter expansion with removal of largest suffix pattern
- `parampre`: Parameter expansion with removal of smallest prefix pattern
- `parambigpre`: Parameter expansion with removal of largest prefix pattern

## Installation

1. Open Visual Studio Code
2. Press `Ctrl+P` to open the Quick Open dialog
3. Type `ext install BashSnippets` to find the extension
4. Click the `Install` button, then the `Enable` button

## Usage

To use the snippets, open a Bash file, and start typing the name of a snippet. You'll see a dropdown list of suggestions. You can navigate through this list with `Up` and `Down` arrow keys. To insert a snippet, press `Enter`.

## Contributing

If you have suggestions for improving the BashSnippets, please [open an issue or
submit a pull request](https://github.com/evildevill/BashSnippets).

## License

[MIT](LICENSE) © Waseem Akram