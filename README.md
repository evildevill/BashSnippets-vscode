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
- `paramrepdef` : - Parameter expansion with replacement and default value
- `cd` : - Change directory
- `mkdir` : - Make directory
- `touch` : - Create a new file
- `rm` : - Remove a file
- `ls` : - List directory contents
- `grep` : - Search for a pattern in a file
- `find` : - Find files in a directory
- `tar` : - Create a tar archive
- `untar` : - Extract a tar archive
- `wget` : - Download a file from the internet
- `curl` : - Transfer data from or to a server
- `chmod` : - Change file permissions
- `chown` : - Change file owner and group
- `chgrp` : - Change file group
- `ps` : - List running processes
- `kill` : - Kill a process
- `top` : - Display Linux processes
- `free` : - Display amount of free and used memory in the system
- `df` : - Display disk usage
- `du` : - Display disk usage statistics
- `uname` : - Print system information
- `date` : - Display the system date and time
- `uptime` : - Show how long the system has been running
- `who` : - Show who is logged on
- `w` : - Show who is logged on and what they are doing
- `finger` : - Display information about user
- `id` : - Print real and effective user and group IDs
- `last` : - Show last logins of users and ttys
- `whoami` : - Print the effective userid
- `groups` : - Print the groups a user is in
- `hostname` : - Print the system hostname
- `dmesg` : - Print or control the kernel ring buffer
- `lsmod` : - Show the status of modules in the Linux Kernel
- `lspci` : - List all PCI devices
- `lsusb` : - List all USB devices
- `lscpu` : - Display information about the CPU architecture
- `lsblk` : - List block devices
- `lshw` : - List hardware
- `lsscsi` : - List SCSI devices
- `lsdev` : - List devices
- `checknet` : - Check if the internet is on or off
- `checknetdns` : - Check if the internet is on or off using DNS
- `checknetdnsretry` : - Check if the internet is on or off using DNS and retry every 5 seconds
- `checknetdnsretrytimeout` : - Check if the internet is on or off using DNS and retry every 5 seconds with a timeout of 60 seconds
- `checknetdnsretrytimeouterr` : - Check if the internet is on or off using DNS and retry every 5 seconds with a timeout of 60 seconds and an error message
- `checknetdnsretrytimeouterrex` : - Check if the internet is on or off using DNS and retry every 5 seconds with a timeout of 60 seconds and an error message and exit
- `casepattern` : - case statement with pattern matching
- `select` : - select loop for menu-like interfaces
- `getopts` : - getopts loop for processing command-line options
- `fileexist` : - check if a file exists
- `direxist` : - check if a directory exists
- `fileread` : - check if a file is readable
- `filewrite` : - check if a file is writable
- `fileexec` : - check if a file is executable
- `fileowner` : - check if a file is owned by the user
- `filegroup` : - check if a file is owned by the group
- `fileempty` : - check if a file is empty
- `filesize` : - check if a file is larger than 0 bytes
- `filetype` : - check the type of a file
- `fileperm` : - check the permissions of a file
- `fileage` : - check the age of a file
- `filecontent` : - check the content of a file
- `filecontentregex` : - check the content of a file with a regex
- `filecontentregexcase` : - check the content of a file with a case insensitive regex
- `filecontentregexword` : - check the content of a file with a whole word regex
- `filecontentregexwordcase` : - check the content of a file with a whole word case insensitive regex
- `filecontentregexwordlinenum` : - check the content of a file with a whole word regex and line number
- `filecontentregexwordcaselinenum` : - check the content of a file with a whole word case insensitive regex and line number
- `filecontentregexwordlinenumfile` : - check the content of a file with a whole word regex and line number and file name
- `filecontentregexwordcaselinenumfile` : - check the content of a file with a whole word case insensitive regex and line number and file name
- `filecontentregexwordlinenumfilecount` : - check the content of a file with a whole word regex and line number and file name and count
- `filecontentregexwordcaselinenumfilecount` : - check the content of a file with a whole word case insensitive regex and line number and file name and count
- `filecontentregexwordlinenumfilecounterr` : - check the content of a file with a whole word regex and line number and file name and count and error message
- `filecontentregexwordcaselinenumfilecounterr` : - check the content of a file with a whole word case insensitive regex and line number and file name and count and error message
- `filecontentregexwordlinenumfilecounterrex` : - check the content of a file with a whole word regex and line number and file name and count and error message and exit
- `filecontentregexwordcaselinenumfilecounterrex` : - check the content of a file with a whole word case insensitive regex and line number and file name and count and error message and exit
- `whilecond` : - while loop with a specified condition
- `break` : - break statement to exit a loop or switch statement
- `continue` : - continue statement to skip the rest of a loop and start the next iteration
- `sleep` : - pause the script for a specified number of seconds
- `awk` : - AWK one-liner for text processing
- `sed` : - SED one-liner for text processing
- `tail` : - display the last part of a file
- `head` : - display the first part of a file
- `sort` : - sort lines of text files
- `uniq` : - report or filter out repeated lines in a file
- `cut` : - remove sections from each line of a file
- `paste` : - merge lines of files
- `awkscript` : - AWK script template
- `sedscript` : - SED script template
- `grepcolor` : - search for a pattern in a file with color
- `greplinenum` : - search for a pattern in a file with line number
- `grepword` : - search for a pattern in a file as a whole word
- `grepwordlinenum` : - search for a pattern in a file as a whole word with line number
- `grepwordlinenumfile` : - search for a pattern in a file as a whole word with line number and file name
- `grepwordlinenumfilecount` : - search for a pattern in a file as a whole word with line number and file name and count
- `grepwordlinenumfilecounterrex` : - search for a pattern in a file as a whole word with line number and file name and count and error message
- `grepwordlinenumfilecounterrexexit` : - search for a pattern in a file as a whole word with line number and file name and count and error message and exit
- `grepwordlinenumfilecounterrexexitcase` : - search for a pattern in a file as a whole word with line number and file name and count and error message and exit and case insensitive
- `forfile` : - loop through files in a directory
- `casepat` : - case statement with a specific pattern
- `select` : - create a select menu in a script
- `fnparam` : - function with parameters and default values
- `ifempty` : - if statement for checking if a variable is null or an empty string
- `untilcond` : - until loop with a specified condition
- `casemulti` : - case statement with multiple patterns
- `loopexec` : - execute a command in a loop for each element in a collection
- `iffileexists` : - if statement for checking if a file exists
- `ifdirexists` : - if statement for checking if a directory exists
- `ifcommandexists` : - if statement for checking if a command exists in the system
- `readfile` : - read lines from a file in a loop
- `fnvarargs` : - function with a variable number of arguments
- `forlineinfile` : - loop through lines in a file
- `getscriptdir` : - get the directory of the script
- `caseesac` : - case statement with esac
- `ifinstalled` : - check if a program is installed
- `ifroot` : - check if a user has root privileges
- `outputtofile` : - redirecting output to a file
- `outputerrorstofile` : - redirecting output and errors to a file
- `ifreadable` : - if statement for checking if a file is readable
- `ifwritable` : - if statement for checking if a file is writable
- `ifexecutable` : - if statement for checking if a file is executable
- `ifsubstring` : - if statement for checking if a string contains a substring
- `ifstartswith` : - if statement for checking if a string starts with a prefix
- `ifendswith` : - if statement for checking if a string ends with a suffix
- `commentblock` : - useful comment block
- `readvalidate` : - read and validate user input

## Installation

1. Open Visual Studio Code
2. Press `Ctrl+P` to open the Quick Open dialog
3. Type `ext install WaseemAkram.bashnsippets` to find the extension
4. Click the `Install` button, then the `Enable` button

## Usage

To use the snippets, open a Bash file, and start typing the name of a snippet. You'll see a dropdown list of suggestions. You can navigate through this list with `Up` and `Down` arrow keys. To insert a snippet, press `Enter`.

## Contributing

If you have suggestions for improving the BashSnippets, please [open an issue or
submit a pull request](https://github.com/evildevill/BashSnippets-vscode).

## License

[MIT](LICENSE) © Waseem Akram

## Support

If you like this extension, you can support me by:

- Star this repository on [GitHub](https://github.com/evildevill/BashSnippets-vscode)
- [Follow me on GitHub](https://github.com/evildevill)
- [Support me on Patreon](https://www.patreon.com/hackerwasii)
- [Follow me on Facebook](https://facebook.com/hackerwasii)
- [Follow me on Instagram](https://instagram.com/wasii_254)
- Your support is greatly appreciated! 🙏

**Enjoy!**

**[Waseem Akram](https://hackerwasii.com)**