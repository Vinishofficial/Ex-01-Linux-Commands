
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

 <img width="807" height="75" alt="image" src="https://github.com/user-attachments/assets/b14c8334-6e16-4558-bf32-018cbbdf9f8c" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="775" height="133" alt="image" src="https://github.com/user-attachments/assets/132946c0-1265-4b4a-b572-8e7ea4d4108c" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir cloud

<img width="377" height="172" alt="image" src="https://github.com/user-attachments/assets/e1f39f3d-9177-46fc-9b21-e75254296b61" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir cloud

<img width="436" height="138" alt="image" src="https://github.com/user-attachments/assets/bb8f1adc-76ac-4a37-bda3-ab354d27d679" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd cloud

<img width="377" height="121" alt="image" src="https://github.com/user-attachments/assets/02b90973-87ae-467a-b0fc-2c66be7ec71f" />



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat test2.txt

<img width="337" height="70" alt="image" src="https://github.com/user-attachments/assets/3f7c39d8-689b-43fe-8836-d40295ffc3a4" />


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp test.txt test2.txt

<img width="345" height="145" alt="image" src="https://github.com/user-attachments/assets/d75b178d-7401-4649-b8b9-a77111937633" />




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit test.txt

<img width="1272" height="291" alt="image" src="https://github.com/user-attachments/assets/eaa13be3-b1a6-400c-820b-5efcc4cd0c77" />



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su kali

<img width="451" height="148" alt="image" src="https://github.com/user-attachments/assets/51f92e4b-1de2-4877-a038-afb7965e72d0" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv test.txt Documents

<img width="495" height="71" alt="image" src="https://github.com/user-attachments/assets/1aa8afc5-1924-4cb0-a434-18120a9f7d04" />


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="632" height="83" alt="image" src="https://github.com/user-attachments/assets/6105ef30-bd24-4edd-8fb6-081869328f77" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head test.txt

<img width="533" height="97" alt="image" src="https://github.com/user-attachments/assets/0497f3b1-24c3-46fc-94f4-076edfa99aab" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail test.txt

<img width="531" height="117" alt="image" src="https://github.com/user-attachments/assets/c76dd98b-048d-4980-be95-ebcf3a5900bb" />


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1911" height="141" alt="image" src="https://github.com/user-attachments/assets/11ee3d10-60cf-4395-aef1-64094883b87f" />



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


<img width="700" height="101" alt="image" src="https://github.com/user-attachments/assets/7dfdda7f-aeb4-4249-b768-14a4dd3228c4" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="961" height="436" alt="image" src="https://github.com/user-attachments/assets/5ad9a96f-4891-413c-9f30-6abb8bd97ed3" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


<img width="722" height="152" alt="image" src="https://github.com/user-attachments/assets/49dfa30d-0008-41e2-b7dd-af50e3ece271" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort test.txt


<img width="582" height="110" alt="image" src="https://github.com/user-attachments/assets/4319039a-b289-474d-a783-da2c1be16598" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="612" height="288" alt="image" src="https://github.com/user-attachments/assets/5a557705-373c-4517-9868-d9bbe3240895" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="627" height="156" alt="image" src="https://github.com/user-attachments/assets/e3be5d16-cb22-4b7d-a9e8-c930526495ab" />



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="1305" height="357" alt="image" src="https://github.com/user-attachments/assets/826e2b59-df6b-48ae-b848-0de029fa20dc" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="555" height="131" alt="image" src="https://github.com/user-attachments/assets/efbd1c4f-9a18-40a2-8344-ca6b9061239f" />






















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
