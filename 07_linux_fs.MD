# Linux File System

## 1 root folder
<img src="./assets/linuxfs.png" style="float;left">
<br>

# windows file systems
### windows file systems doesn't have one root folder 
it has multiple root folders
<img src="./assets/windowsfs.png" style="float;left">

# Linux file system overview
in linux file system each user has its own space.
only `root` user has its own space called `/root` 
programs installed system wide, are available for all users on that pc.
#most essential directories
# /bin - binaries

basic command for instance `ls`, `cp` are stored in the `/bin` directory

# /sbin - system binaries

system wide binaries basicly these commands need super user privileges to execute.
essential system binaries programs that admin would use.

# /lib - library
The /lib directory contains kernel modules and those shared library images (the C programming code library) needed to boot the system and run the commands in the root filesystem, ie. by binaries in /bin and /sbin. Libraries are readily identifiable through their filename extension of *.so. Windows equivalent to a shared library would be a DLL (dynamically linked library) file. They are essential for basic system functionality. Kernel modules (drivers) are in the subdirectory /lib/modules/'kernel-version'. To ensure proper module compilation you should ensure that /lib/modules/'kernel-version'/kernel/build points to /usr/src/'kernel-version' or ensure that the Makefile knows where the kernel source itself are located.

# /usr - user

# /opt - Optional
where third-party programs will be installed `chrome`, `brave`, `teams` and so on.

`usr/local` -> programs, which split it's components
`/opt` - > programs, which NOT split its components

# /boot - booting
contains files required for booting

# /etc 
place where configuration for system-wide applications is stored 
for instance nginx config or network config and so on ...