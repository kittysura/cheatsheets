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

### How to install a package in Archlinux?

A. Use `sudo pacman -S package-name`

### How to uninstall or remove a package in Archlinux?

A. Use `sudo pacman -R package-name`

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

