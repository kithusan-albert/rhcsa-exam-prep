###### *Source:* RHCSA Red Hat Enterprise Linux 9 by Asghar Ghori - Essential System Commands

The basic syntax of a Liunx command: 

Many commands have preconfigured default options and arguments. Other commands do require at least one option or argument in order to work. 

    Options : (a.k.a a switch of flag) are optional. Option to specify zero or more options with a command.

    Arguments : May be optional or mandatory depending on the command and its usage. 

    An option may start with a single hyphen character (-), short-option.
        short-option : Each individual letter in the option represents a separate option (-la, for instance, I and a are two options)
    
    An option may also start with two hyphen character (--), long-option
        long-option : All letters in is collectively identified as a single option (-all is one option)

> **Listing Files and Directories**

| Command | Description |
| --- | --- |
| ls | list files in the current directory |
| ls -l | list files with detail information |
| ls -ld | list files with  without showing its contents |
| ls -lh | list with with their sizes in human-friendly format |
| ls -la | list all files, including hidden files |
| ls -lt | list files sort output last modification time, with the newest file first |
| ls -R | lists all files and directories recursively, includes all subdirectories, their subdirectories, and so on. |

> **Navigating Directory**

| Command | Description |
| --- | --- |
| pwd | Display a user's current location in the directory tree |
| cd | Change the current working directory, specify with a relative path or absolute path |
| cd ~ | Change directory to home |
| cd / | Change directory to root |
| cd - | Return to the previous directory you were in|
| tree | List a hierarchy of directories and files, add |
| tree -a | Include hidden files in the output|
| tree -d | Excludes files from the output, only directories|
| tree -h | Display file sizes in human-friendly format|
| tree -f | Print the full path of each file and directory|
| tree -p | Include file permission of each file and directory|
| tty | Print the file name of the terminal connected to the current session|
| uptime | Display the system current time, length of time it has been up for, number of users currently logged in, and the average CPU load over the past 1, 5 and 15 minutes.|
