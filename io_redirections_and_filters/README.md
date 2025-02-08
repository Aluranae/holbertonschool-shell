# Shell, I/O Redirections and filters

In this project I learned how permissions work in Shell through 16 tasks.

*However, here are the requirements that have been requested:*

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable
* You are not allowed to use sed or awk




# **What does it do?**

## **An explanation of how each script and permissions works**


### **Task 0**
* [Hello World](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/0-hello_world)

While using the _su_ command the script prints "Hello, World", followed by a new line to the standard output.

### **Task 1**
* [Confused smiley](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/1-confused_smiley)

While using the echo .._ command the script displays a confused smiley "(Ôo)'.

### **Task 2**
* [Let's display a file](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/2-hellofile)

While using the _cat .._ command the script display the content of the /etc/passwd file.

### **Task 3**
* [What about 2?](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/3-twofiles)

While using the _cat .._ command the script display the content of /etc/passwd and /etc/hosts.

### **Task 4**
* [Last lines of a file](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/4-lastlines)

While using the _tail .._ command the script display the last 10 lines of /etc/passwd

### **Task 5**
* [I'd prefer the first ones actually](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/5-firstlines)

While using the _tail .._ command the script display the first 10 lines of /etc/passwd

### **Task 6**
* [Line #2](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/6-third_line)

While using the _tail .._ command the script display the first 10 lines of /etc/passwd

The file iacta will be in the working directory

* You’re not allowed to use sed

_Note: The output will differ, depending on the content of the file iacta._

### **Task 7**
* [It is a good file that cuts iron without making a noise](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/6-third_line)

While using the _echo -e .._ command the script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.