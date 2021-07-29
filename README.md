# Bash{zsh} Commands Cheatsheet

Here's a cheatsheet I'm using to remember some of the most common `bash` commands.

### Navigating the file system

##### The `cd` command:
This is a command that stands for `change directory` that is commonly used to navigate through a file system. 

Example: `cd "path/to/directory/"`

##### the `ls` command:

This is a command that stands for `list` that is used to view the contents (files and directories) inside of the current directory. Use the argument -l (ls -l) to get even more information about each of the files, including the permissions, owner and date created.

Example: `ls -or- ls "path/to/directory"`

##### the `pwd` command: 

This is a command that stands for `print working directory` that is used to prints the complete path of the current working directory.

Example: `pwd`

##### the `open` command:

When browsing a directory, you may encounter a file that you wish to open on your Mac. That's where the open command comes in. Typing this command followed by a space and the filename will open the file with the app that can open that file type on the Mac. When typing the filename, you don't need to type the full name, partially type what you can, then press tab to autocomplete the remaining text.

Example: `open "file name"`

##### the `cp` command:

This is a command that stands for `copy` that is used to create a copy of any file from one location to another, or just simply making a copy of the same file with a new name. When specifying the first argument, include the originating file that you wish to copy followed by a space and a full path, filename and extension of where you want the copy to be placed when the command is executed. The Terminal will return when the copy has been completed.

Example: `cp "file name" "new file name" -or- cp "file name" ~/path/to/directory/`

##### the `mv` command:

This is a command that stands for `move` that is used when you don't want to copy a file, but instead move it, use the same format of the cp command, but instead replace 'cp' with 'mv'. This will perform a file move from one location to another, removing the file from the original location and putting it into the new location.

Example: `mv "file name" "~/path/to/new/file/location"`

##### the `touch` command:

This is a command that is used to create a new blank file. After you create the new file, you can open it in a text editor by using the open command.

Example: `touch README.md`

##### the `mkdir` command:

This is a command that stands for `make directory` that is used to create a directory (folder). When you need a place to store new files, just use this command to add a new directoy in the current working directory, or specify a full path to the location where you want the new directory to be placed. 

Example: `mkdir "/path/to/new/directory"`

##### the `rmdir` command: 

This is a command that stands for `remove directory` that is used to delete and empty directory altogether.

Example: `rmdir "/path/to/directory"`

##### the `rm -R` command:

Ths is a command that is for when you want to remove an entire directory that might contain other directories or files, then the `rm -R` command is where you will turn. This command is irreversible,  (unlike deleting files in the Finder and being able to restore them from the Trash). When this command is executed, all files and directories inside of the path you specify will be deleted immediately.

Example: `rm -R "/path/to/root/directory/"`

##### the `sudo` command:

This is a command that stnads for `super user do` that allows you to elevate your user privileges while executing the command to administrator privileges. This is required for some commands to run —for instance removing a file that is owned by another user. When you run this command, you will see a password field appear in the Terminal where you will need to type your user account password to finish the command execution. 

Example: `sudo "command"`

##### the `top` command:

You'll see the stats of your system updated in the Terminal window, including the memory, CPU and disk utilization. You'll also see a running list of the top apps using the CPU and their state, ports used, memory per app and more, without needing to open the Activity Monitor app on your Mac. This command will execute until you close the Terminal window or press Control + C to return execution back to the CLI.

Example: `top`

##### the `q` command:

This is a command that stands for `quit`. This is used for commands that in perpetuity when executed, you can end execution of the process by pressing the q key on your keyboard. Alternatively you can also press Control+C.

Example: `q` - After executing a command, such as `top`, press `q` to exit.

##### the `clear` command:

This is a command to `clear` out all previuosly typed commands from the Terminal view and gives you a blank clean slate to work from. Instead of typing clear, you can also alternativly press `Command+K` to preform the same action.

Example: `clear`

##### the `ditto` command:

The `ditto` command will execute a copy of all of the contents of one folder into another folder that you specify. This is great for when you need to start a new project and use an older project as a base, or just copy files in a folder from your computer to an external drive. Add a -`V` as in the example below to get verbose output for each file copied.

Example: `ditto -V MyFolder MyNewFolder`

##### the `whatis` command:

This is a command that is used to get a short description of a command and `what it does` on your Mac.

Example: `whatis command`

##### the `man` command:

Most commands in the Terminal ship with a manual that allows you to get help or ;ook up arguments and other information on what a command does. Use this man command when you want to find more information about a particular command.

Example: `man "command"`

##### the `exit` command:

This command will close out the current session in the Terminal. You can also simply close the window, but that may not be possible when you're using SSH through Terminal to access a remote machine. In this instance, you'll want to use exit to hang up that remote connection before closing the window.

Example: `exit`




