###### *Source:* RHCSA Red Hat Enterprise Linux 9 by Asghar Ghori - Basic File Management

Linux supports different types of files that are identified based on the kind of data they store or represent. Files can be stored in plain text or binary formats, which are common types. Some special files, such as device files, represent interfaces to hardware devices, while symbolic links are special files that point to other files or directories on the filesystem.

    Placeholder

> **Common File Types**

    RHEL supports seven types of files: regular, directory, block special device, character special device, symbolic link, named pipe, and socket. 

        Regular : Files many contain text or binary data. Such as shell scripts or commands in the binary form.

        
        Block special device and character special device : 
        These two types of device files are used by the operating system to communicate with peripheral devices. 

        Named pipe and sockets : Is used in inter-process communication

        

| Command | Description |
| --- | --- |
| file | Determine the type of file, examines the file's content (rather than its extension) |
| stat | Provide detailed information about a file or a file system (such as size, permissions, timestamps, ownership, etc) |

