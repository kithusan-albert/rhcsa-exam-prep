###### *Source:* RHCSA Red Hat Enterprise Linux 9 by Asghar Ghori - Linux Directory Structure and File Systems



### 1. **Linux Directory Structure and File Systems:**

    File systems contain files and subdirectories.
<p align="center">
    <img src="https://github.com/user-attachments/assets/51b2d168-0389-44da-99c2-c54671a7308f" alt="Linux Directory Structure" width="500">
</p>

    Files system hold static data, dynamic or variable information
        - Static data refers to file content that remains unchanged unless modified explicitly.
        - Dynamic or variable data refers to file content that is modified and updated as required by system processes.
        - Static diretories normally contain command, configuration files, librarym routines, kernel files, device files, etc.
        - Dynamic directories contain log files, status files, temporary file, etc.
        
    The forward slash ( / ) is used as a directory separator in directory path.

    
### 2. **File System:**

>  **Directories**

    /ect : directory holds system configuration files.
    /root : This is the default home directory location of the root user.
    /mnt : This is the directory used to mount file systems temporarily. 
    /boot : Boot file system contains the Linux kernel, boot support files, and boot configuration files. 
    /home : Home file system is to store user home directories and other user contents.
    /opt : Used to hold additional software that may need to be installed on the system. A subdirectory is created for each installed software

>  **UNIX System Resources Directory (/usr)**

    /usr: usr contains most of the system files.
        - /usr/bin : The binary directory contains crucial user executable commands.
        - /usr/sbin : Commands that are required at system boot, and those that require the root user privileges in order to run are stored in the system binary directory.
        - /usr/lib and /usr/lib64 : Contains shared library routines required by many commands and programs located in the /usr/bin and /usrs/sbin directories, other application and programs for their sucessful installation and operation.
        - /usr/lib directory also stores system initialization and service management programs.
        - /usr/lib64 contains 64-bit shared library routines.

    /usr/include : This directory contains header files for C language.
    /usr/local : This directory serves as a system administrator repository for storing custom commands and tools. 
        - /usr/local/bin contains executables
        - /usr/local/etc hold configurations files
        - /usr/local/lib and /usr/local/lib64 holds libray routines. 

    /usr/share : This directory serves as the location for manual pages, documentation, sample templates, configuration file, etc., that may be shared with other Linux platforms. 

    usr/src : This Directory is used to store source code.
    


    

    
