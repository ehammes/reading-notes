# Prep: Practice in the Terminal

## The Command Line

- [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php) - What is it, how does it work and how do I get to one.
- [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php) - An introduction to the Linux directory system and how to get around it.
- [More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php) - Find out some interesting characteristics of files and directories in a Linux environment.
- [Manual Pages](https://ryanstutorials.net/linuxtutorial/manual.php) - Learn how to make the most of the Linux commands you are learning.
- [File Manipulation](https://ryanstutorials.net/linuxtutorial/filemanipulation.php) - How to make, remove, rename, copy and move files and directories.
- [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php) - A quick reference for the main points covered in this tutorial.

### Observations and Learnings

- Good reminders and callouts on how to navigate the terminal, especially referencing the cheat sheet on a regular basis
- Paths sometimes get me confused, adding notes for reference:
  - `~` (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
  - . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
  - .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
- I plan to utilize the terminal more in the near future, for example when removing, renaming, creating, and copying files. The file manipulation page provides a good outline on how to achieve these tasks in the terminal.
- TAB completion - Start typing and press TAB. The system will auto complete the path. Press TAB twice and it will show you your alternatives.
- Use 'cp' for copy, 'mv' for move, and 'rm' for remove
