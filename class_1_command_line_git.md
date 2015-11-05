#Unix/Linux/MacOSX Commands
* `~` : This symbol means "home" on the UNIX command line and can navigate you back to your home directory.
* `/` : This symbol means "root", the ultimate parent directory. This exists even before "home."
* `whoami` : This makes the terminal output the current user name.
* `pwd` : print working directory. This shows you the entire path of the directory you are currently in. Use this if you get lost in the network of directories.
* `cd` : change directory. This helps you navigate between various directories
* `ls` :  list. This shows you all of the files AND directories that are in the directory you are currently in. adding a "-a" will show you all of the hidden "." directories.
* `cd ..` : this navigates you to the directory immediately above the current directory you are in.
* `mkdir` : make directory: create a new directory.
* `touch` : create a new file, but not actually do anything to it.
* `cat` : concatenate, which can either show you the entire contents of a file or allow you to create a new file, depending on which flags/actions you add to the command.
* `.` : denotes current directory. Typing cd . means nothing will happen. However, in a command, it can indicate all of the contents in the current directory.
* `rm` : remove file – permanently deleting a file.
* `rm -rf` : forcefully deleting a directory and all of its associated subdirectories, files, etc.
* `man` : manual – pulling up the definitions of various commands.
* ../.. moving up 2 directory levels.
* subl . : opening up that particular folder in sublime text
* open . : opens up a Finder window wherever you are currently located.
* absolute paths : go straight from the root to the exact directory
* command K : clear the terminal page (or just type clear)
* up/down arrows allow you to move through your command history
* hitting tab allows you to auto-complete the name of a particular folder or directory within that parent directory

# Basic Git commands
* `git init` : initiate. this creates a hidden .git folder in that particular directory.
* `git add .` : stage the latest changes you have made to your code.
* `git add hello.txt` : staging that particular file to your git repository.
* `git status` : seeing which files have been modified/which files have been added/which files need to be added
* `git commit -m 'created hello.txt` : committing a modification and giving it a particular description
* `git push origin master` : the inital push of whatever you're working on to the cloud server.