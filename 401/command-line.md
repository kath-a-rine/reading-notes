# [Practice in the Terminal](https://ryanstutorials.net/linuxtutorial/)

## The Command Line

"The command line, or terminal, is a text based interface to the system." You can have several command lines open. In 301, I found it helpful to have one open for front end work and another for back end, since I would need to do separate commands for each and wanted to commit often.

## Basic Navigation Commands

- **`pwd`** - Print Working Directory
- **`ls`** - list
- **`cd`** - change directory

***"A path is a means to get to a particular file or directory."*** The top of the structure is the **root** directory.

**Absolute paths** specify a location in relation to the root directory. **Relative paths** specify a location in relation to where you are currently within the system.

> *  ~ (tilde) - *This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents*
> * . (dot) - *This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).*
> * .. (dotdot) - *This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.*

## More About Files

- **`ls -a`** - lists all files of a directory including hidden files (hidden files begin with `.`)
- **`file`** - identifies the type of file

## Manual Pages

`man <command to look up>` - Manual pages explain every available command and what they do.

`man -k <search term>` - keyword search for all manual pages contained the search term

`/<term>` - perform a search for 'term'

`n` - select the next found item after a search

## File Manipulation

- **`mkdir`** - make directory
- **`-p`**  - make a parent directory
- **`-v`** - tells us what has been done (ex. `mkdir: created directory 'file/file/newDirectory'`)
- **`rmdir <Directory Name>`** - remove directory
- **`touch <new filename>`** - creates blank file
- **`cp <source> <destination>`** - creates duplicate file
- **`mv <source> <destination>`** - move file or directory. You can rename a file by "moving" it to the same source with a different name.
- **`rm <file>`** - removes(deletes) a file

[Linux Tutorial - Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)