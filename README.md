# Ex-01-Linux-Commands

### NAME: Devanand C
### REG NO: 212223060043

## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 
<img width="945" height="207" alt="is" src="https://github.com/user-attachments/assets/0e59628a-1a96-42d1-aa47-036d7a60f101" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="937" height="68" alt="pwd" src="https://github.com/user-attachments/assets/601ebd6f-4a21-4913-9fd5-6b5bc644b5f9" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="942" height="61" alt="mkdir" src="https://github.com/user-attachments/assets/5f83c0be-00a7-4795-9324-3e70071703c9" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="940" height="63" alt="rmdir" src="https://github.com/user-attachments/assets/11dfc64c-6bab-40da-8c74-e4afb6a264c6" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="935" height="69" alt="cd" src="https://github.com/user-attachments/assets/5b041eef-4d8e-4b4a-a238-ee104d1390a5" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="936" height="112" alt="cat" src="https://github.com/user-attachments/assets/bed8bfc9-9d30-49da-8b2a-595d5b0c1f8e" />
 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="939" height="68" alt="cp" src="https://github.com/user-attachments/assets/c1aa3294-82bf-4617-a32f-fd7b41e95c88" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="939" height="30" alt="gedit" src="https://github.com/user-attachments/assets/e58db865-e05f-4cc3-9672-287f3adba2b5" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="943" height="102" alt="su" src="https://github.com/user-attachments/assets/a0efa093-9520-4022-8cbf-71cf35df1f8c" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="931" height="33" alt="mv" src="https://github.com/user-attachments/assets/9d9a6323-04fc-4738-9878-b58f97b1f992" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="940" height="229" alt="rename" src="https://github.com/user-attachments/assets/b05b4e30-7c4c-4ac0-a3dd-1732f80a7a03" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="937" height="308" alt="head" src="https://github.com/user-attachments/assets/91fc4f93-4edd-46ba-a293-63ff644e3432" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="838" height="221" alt="tail" src="https://github.com/user-attachments/assets/43b15cf9-fd55-447e-87f3-d495ae8f7b35" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="941" height="101" alt="id" src="https://github.com/user-attachments/assets/f7a7cfba-019b-4df2-a837-d30b4f7acd0e" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="942" height="62" alt="grep" src="https://github.com/user-attachments/assets/118c4d6e-b541-4438-b54e-f55a916e8bfd" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="938" height="170" alt="tr" src="https://github.com/user-attachments/assets/4d2562aa-4b52-4df2-9231-1cd38d4cff93" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="886" height="242" alt="chown" src="https://github.com/user-attachments/assets/39ce891f-c42d-4a0f-9c48-f1061eeda1de" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="944" height="82" alt="make" src="https://github.com/user-attachments/assets/f34e8c42-4828-431e-b819-8a47bc825611" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="943" height="192" alt="ifconfig" src="https://github.com/user-attachments/assets/0222d11b-cf9c-4470-9650-4e92c910fea7" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="940" height="55" alt="host" src="https://github.com/user-attachments/assets/91b89eec-f9b8-4aea-8c5f-a3c42fb4fbf4" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="935" height="251" alt="gzip" src="https://github.com/user-attachments/assets/617e6b7b-9ef7-4d65-ba00-a89d6297309c" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="929" height="176" alt="sort" src="https://github.com/user-attachments/assets/5c69a104-d2b5-48ae-9153-a3a7c0d48e0d" />
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="940" height="242" alt="cal" src="https://github.com/user-attachments/assets/2f6a4a67-3fbf-4973-9803-72792c7a1c99" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="935" height="247" alt="clear" src="https://github.com/user-attachments/assets/6ade4d94-e1a8-448a-88d2-fd8d9440ccf7" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="939" height="89" alt="mail" src="https://github.com/user-attachments/assets/b6e3ddd7-88c8-45b8-9a6e-2fd6c2e6f858" />
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="935" height="305" alt="df" src="https://github.com/user-attachments/assets/1bbd9121-0f2f-448d-a130-ce724c358f96" />


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
