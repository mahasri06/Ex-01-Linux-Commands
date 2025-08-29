# Ex-01-Linux-Commands


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



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>



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


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..




### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>



### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal




### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>



### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df



### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## OUTPUT :

<img width="448" height="126" alt="uname" src="https://github.com/user-attachments/assets/92ccfe82-4501-4007-87e7-e93654b23265" />  
<br>  <br>
<img width="412" height="122" alt="cat" src="https://github.com/user-attachments/assets/13d130b5-549d-447b-ba73-b4772ce8b66d" />
<br>  <br>
<img width="430" height="78" alt="ls" src="https://github.com/user-attachments/assets/3826af4a-85d5-4690-bdcb-7d87b04a4e50" />
<br>  <br>
<img width="319" height="173" alt="cal" src="https://github.com/user-attachments/assets/2789ef90-b8c3-470d-85c4-fb6080796505" />
<br>  <br>
<img width="384" height="53" alt="chmod" src="https://github.com/user-attachments/assets/8ca9561a-c434-4a08-a59b-5bc68e8a41a4" />
<br>  <br>
<img width="397" height="206" alt="head" src="https://github.com/user-attachments/assets/2ea99bdf-9e3e-4d53-af58-853343116e03" />
<br>  <br>
<img width="933" height="97" alt="id" src="https://github.com/user-attachments/assets/20cec62a-90fb-4cbf-a90a-6dc804968752" />
<br>  <br>
<img width="354" height="267" alt="cp" src="https://github.com/user-attachments/assets/f31be7fc-1874-4cac-85f1-986591329762" />
<br>  <br>
<img width="370" height="93" alt="mkdir cd" src="https://github.com/user-attachments/assets/25de3f32-418b-48f6-bbbc-630652a957ac" />
<br>  <br>
<img width="829" height="152" alt="mv" src="https://github.com/user-attachments/assets/dc0f06ad-afb4-4e4a-a39e-35d6c1cd43c0" />
<br>  <br>
<img width="285" height="54" alt="pwd" src="https://github.com/user-attachments/assets/aed68783-448e-438d-8363-fb725c297079" />
<br>  <br>
<img width="416" height="207" alt="tail" src="https://github.com/user-attachments/assets/8870687c-4cc8-42ff-b8a5-0768c79fd552" />
<br>  <br>
<img width="281" height="56" alt="rmdir" src="https://github.com/user-attachments/assets/b2c4ccdf-7740-4ae2-8a0b-a2ce29aa0ed8" />
<br>  <br>
<img width="326" height="127" alt="tr" src="https://github.com/user-attachments/assets/6e5549fd-9231-47ba-b039-9178b9a16172" />



## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
