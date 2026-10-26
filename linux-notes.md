The Terminal provides the window you type into, while the shell runs inside it.
The $ sign shows that the shell is waiting for input from a normal user.

-Echo command displays the text provided back to the terminal
(Eg: $ Echo "linux is good." linux is good. is displayed)

-pwd command(stands for print working directory) prints the current working directory you are in. In case you forgot where you are you may use it.
The entire filesystem starts from a single top level directory called the root directory, represented by a forward slash (/).
pwd is useful when:
1. You are following instructions and need to comfirm your location
2. a command failed because a file path is wrong
3. You are lost in several directories and forgot where you are
4. You want to copy your directory in another command.

-cd command(stands for change directory) This mostly changes it by going to the previous directory when the directory is wrong it reports an error
An absolute path starts from the root directory eg:(/home/batman/Dsktop)

IF you are already in a directory and want to move to a subdirectory, use a relative path. For instance, if your current location is /home/batman/Pictures 
and it contains a folder named Screenshots you can navigate to it by typing [cd Screenshots]

$ cd . (current directory) represents the directory you are currently in.
$ cd ..(parent directory) moves you one level up to the directory containing your current one.
$ cd ~ (home directory) A shortcut to your personal home directory, like /home/batman.
$ cd - (previous directory) Takes you back to the last directory you were in.

-ls command(stands for list directory) This command lists files and directories so you can inspect your current location or another path
By default, it can list the directories and files in your current directory. However you can also specify a path tolist the contents of a different directory
i.e: [$ ls] OR [$ ls /home/batman]
viewing hidden files or files that begin with [.] you can view them by [$ ls -a]
Getting detailed information we use -l for long format. it shows file permissions, nbr of links, owner, group, size, modification time and name [$ ls -l]
For easier file sizes we add -h for human readable output [$ ls -lh]
Sometimes you may want to change the sort order. The -r option lists files and directories in reverse order [$ ls -r]
You can sort by modification time with -t then reverse with -r [$ ls -lt] and [$ ls -ltr]
You can combine -a and -l to add more functionality. The order doesn't matter, so [ls -al] is the same to [ls -la]
[Common ls Options -a: Show all files, including hidden files. -l: Use long format. -h: Show human-readable sizes with -l. -r: Reverse the sort order. -t: Sort by modification time.-S: Sort by file size.  -d: List the directory itself instead of its contents.]
