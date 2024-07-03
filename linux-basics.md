## LINUX COMMAND TUTORIAL CHEETSHEET

- `cd`		= change directory (changes or navigates dir)
- `ls`		= list contents
- `rm`		= remove contents
- `rmdir`	= removes empty dir
- `cp`		= copy files or dir
- `mv`		= move or rename files or dir
- `pwd`		= print working dir
- `mkdir`	= make dir
- `nano`	= text editor
- `vim`		= text editor
- `ssh`		= secure shell (used for connecting to remote server securely)
- `sudo`	= super user do (used for granting root permission)
- `cat`		= concatonate (used for reading a file)
- `echo`	= prints given text in terminal
- `tee`		= writes to a file
- `grep`	= search using reguler expression key-words
- `less`	= comfortably read large text file or an output with lots of lines
- `find`	= used for searching for contents
- `head`	= used for outputting certain amount of lines from the top of an output or text
- `tail`	= used for outputting certain amount of lines from the bottom of an output or text
- `uptime`	= to check how long a system has been up
- `date`	= to check current date and time
- `htop`	= to check system resource and tasks info
- `free`	= checks memory availability
- `df`		= used for checking storage info
- `lsblk`	= lists connected disks and partitions
- `adduser`	= used for adding new users
- `groupadd`	= used for adding new groups
- `passwd`	= used for assigning or modifying user password
- `chown`	= modify ownership of files and directories
- `chmod`	= modify file or directory permissions
- `usermod`	= modify users

### How to install a package in Archlinux?

A. Use `sudo pacman -S package-name`

### How to uninstall or remove a package in Archlinux?

A. Use `sudo pacman -R package-name`

### How to install a package in Fedora Linux?

A. Use `sudo dnf install package-name`

### How to search packages in Fedora Linux repositories?

A. Use `sudo dnf search package-name`

### How to remove an installed package in Fedora Linux?

A. Use `sudo dnf remove package-name`

### How to list installed packages in Fedora Linux?

A. Use `sudo dnf list --installed`

### How to find a specific installed package in Fedora Linux?

A. Use `sudo dnf list --installed | grep keyword`

### How to redirect console output to a file?

A. Use `command &> file` format

### How to append redirected output to a file?

A. Use `command &>> file` format

### How to read a file with a lot of lines easily?

A. Use `cat file | less` to read output use `command | less`

### What are flags?

A. Flags are specific instructions added to a command. For ex: `pacman -S` where `-S` is
   a flag of pacman command

### How to sort listed file using ls?

A. Use `ls --sort type/time/extension/version/width/none`

### How to make a file?

A. Use command `touch filename`

### How to check for specific file with key-word in listed files?

A. Use `ls | grep key-word`

### How to archive a directory?

A. Use `tar -caf archivename.tar directory`

### How to extract an archive?

A. Use `tar -xaf archivename.tar`

### How to check available memory?

A. Use `free -h` 

### How to check available storage space?

A. Use `df -h`

### How to add a new user?

A. Use `adduser -m username`

### How to assign password to a new user?

A. Use `passwd username`
