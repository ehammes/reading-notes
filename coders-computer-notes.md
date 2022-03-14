# The Coder's Computer Notes

## Choosing a Text Editor

All text editors are pretty similar, but each comes with different features. Select a text editor that you enjoy the most

### What is a text editor?

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer. If you use a text editor that comes on your computer, there are no special bells or whistles at all.

Features that you should look for in a text editor include:

- Code completion: displays possible suggestions based on what has been typed
- Syntax highlighting: makes text more noticeable by colorizing the text and makes it easier to read
- A nice variety of themes (to reduce eye strain and fatigue)
- The ability to choose from a healthy selection of extensions available when you need them

### Third-Party Text Editors

- NotePad++ (Windows)
- TextWrangler (Mac)
- Visual Studio Code (Windows, Mac, Linux)
- Atom (Windows, Mac, Linux)
- Brackets (Windows, Mac, Linux)
- Sublime Text

An IDE (Integrated Development Environment) is really a suite of different software all coming together - a text editor, a file manager, a compiler, and a debugger all in one package.

## Cheat Sheet

### The Command Line

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.
Line 1 presents us with a prompt and then the user enters a command. There must be a space between the command and the first command line argument also. Options are usually listed before other arguments and typically start with a dash (-).
Most commands produce output and listed straight under the issuing of the command. After the command has run, the terminal is ready for another command.

### The Shell, Bash

Within a terminal is a shell and defines how the terminal will behave and looks after running/executing commands. The most common shell is **bash**. Use command **echo** to display a system variable stating your current shell.
Terminal is filled with shortcuts, such as using the up/down and left/right keys.

### Basic Navigation

- pwd: Print Working Directory (tells what your current or present working directory is)
- ls: list the contents of a directory
- cd: change directory (cd [location]), if you run the command cd without any arguments then it will always take you back to your home directory.

### Paths

A path is a means to get a particular file or directory on the system. The file system under linux is a hierarchical structure. At the very top of the structure is what is called the **root** directory

- Absolute: specify a location (file or directory) in relation to the root directory (/)
- Relative: specify a location (file or directory) in relation to where we currently are int he system (they will not begin with a slash)
- ~ (tilde): shortcut for home directory (~/Documents)
- .(dot): reference to your current directory (./Documents)
- ..(dotdot): reference to the parent directory (../../)
- Tab completion: tab key will invoke an auto completion action

### Files

Everything is a file - text file, directory, keyboard, monitor, etc. Linux is an extensionless system.

- file.exe - an executable file, or program.
- file.txt - a plain text file.
- file.png, file.gif, file.jpg - an image.
Remember the following:
- Case sensitivity
- Spaces in names: use quotes
- Escaped characters: use a backslash (\)
- Hidden files and directories: command **ls** will not show hidden files. Use **ls -a** to show hidden files and directories