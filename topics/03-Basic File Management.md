###### *Source:* RHCSA Red Hat Enterprise Linux 9 by Asghar Ghori - Basic File Management

Linux supports different types of files that are identified based on the kind of data they store or represent. Files can be stored in plain text or binary formats, which are common types. Some special files, such as device files, represent interfaces to hardware devices, while symbolic links are special files that point to other files or directories on the filesystem.

    Placeholder

> **Common File Types**

    RHEL supports seven types of files: regular, directory, block special device, character special device, symbolic link, named pipe, and socket. 

        Regular : Files many contain text or binary data. Such as shell scripts or commands in the binary form.

        Block special device and character special device : 
        These two types of device files are used by the operating system to communicate with peripheral devices. 

        Named pipe and sockets : Is used in inter-process communication

        Symbolic link : (a.k.a a soft link or a symlink) is con

        
| Command | Description |
| --- | --- |
| file | Determine the type of file, examines the file's content (rather than its extension) |
| stat | Provide detailed information about a file or a file system (such as size, permissions, timestamps, ownership, etc) |

> **Compression Utility**

    gzip / gunzip : The gzip or gunzip compression utility pair available in Linux for over two decades.
    
    The gzip command is used to create a compressed file of each of the specified files and it adds the .gz extension to each file for identification.

    bzip2 / bunzip2 : The bzip2 command creates a compressed file of each of the specified files and it adds the .bz2 extension

    The function of both gzip and bzip2 is the same, to compress and decompress files.
    
| Command | Description |
| --- | --- |
| gzip file | Compresses the specified file into file.gz |
| gzip -d file.gz | Decompresses the .gz file back to its original state |
| gzip -r | Compresses all files in the directory recursively |
| gzip -k file | Compresses the file while keeping the original file (file.gz and file remain). |
| gzip -l | Option to display compression information about gzipped file and display the filename that will be given when uncompressed |
| bzip2 -z | Compresses  the file |
| bzip2 -d | Decompresses the file to orginal file |
| bzip2 -k | Compresses the file but keep the original |
| bzip2 -v | Shows detailed information during compression, such as progress percentage |
| bzip2 -t | Tests the integrity of the .bz2 file without extracting it |





