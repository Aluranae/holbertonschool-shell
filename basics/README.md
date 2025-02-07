# Shell Basics

In this project I discovered and learned the basics of Shell through 17 tasks.

*However, here are the requirements that have been requested:*
* Allowed editors: vi, vim, emacs
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line
* The first line of all your files should be exactly #!/bin/bash
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, describing what each script is doing
* I am not allowed to use backticks, &&, || or ;
* All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file.




# **What does it do?**

## **An explanation of how each script works**

### **Task 0**
* Where I Am?
While using the _pwd_ command the script prints the absolute path name of the current working directory.

### **Task 1**
* What's in there?
With the the _ls_ command, the script display the contents list of the current directory.

### **Task 2**
* There is no place like home
With the the _cd_ command, the script change the working directory to the user's home directory

### **Task 3**
* The long format
With the the _ls -l_ command, the script display current directory contents in a long format

### **Task 4**
* Hidden files
With the the _ls -al_ command, the script display current directory contents, including hidden files (starting with .). Use the long format.

### **Task 5**
* I love numbers
With the the _ls -lna_ command, the script Display current directory contents.
* Long format
* with user and group IDs displayed numerically
* And hidden files (starting with .)

### **Task 6**
* Welcome
With the the _mkdir /tmp/my_first_directory_ command, the script creates a directory named my_first_directory in the /tmp/ directory.

### **Task 7**
* Betty in my first directory
With the the _mv /tmp/betty /tmp/my_first_directory_ command, the script Move the file betty from /tmp/ to /tmp/my_first_directory.

### **Task 8**
* Bye bye Betty
With the the _rm /tmp/holberton/betty_ command, the script delete the file betty.

* The file betty is in /tmp/my_first_directory

### **Task 9**
* Bye bye My first directory
With the the _rm -r /tmp/.._ command, the script delete the directory my_first_directory that is in the /tmp directory.

### **Task 10**
* Back to the future
With the the _cd -_ command, the script changes the working directory to the previous one.

### **Task 11**
* Lists
With the the _ls -la . .. /._ command, the script lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working
directory and the /boot directory (in this order), in long format.

### **Task 12**
* File type
With the the _file_ command, the script prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

### **Task 13**
* We are symbols, and inhabit symbols
With the the _ls -s /._ command, Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

### **Task 14**
* Copy HTML files
With the the _cp -u .*_ command, Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of
the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html

### **Task 15**
* Let's move
With the the _mv [[:upper:]]* /._ command, the script moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script.

### **Task 16**
* Clean Emacs
With the the _rm *_ command, the script deletes all files in the current working directory that end with the character ~.

### **Task 17**
* Tree
With the the _mkdir -p_ command, the script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more.