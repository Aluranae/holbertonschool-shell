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
* [Hello World](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/0-hello_world)

While using the _su_ command the script prints "Hello, World", followed by a new line to the standard output.

### **Task 1**
* [Confused smiley](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/1-confused_smiley)

While using the echo .._ command the script displays a confused smiley "(Ôo)'.

### **Task 2**
* [Let's display a file](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/2-hellofile)

While using the _cat .._ command the script display the content of the /etc/passwd file.

### **Task 3**
* [What about 2?](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/3-twofiles)

While using the _cat .._ command the script display the content of /etc/passwd and /etc/hosts.

### **Task 4**
* [Last lines of a file](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/4-lastlines)

While using the _tail .._ command the script display the last 10 lines of /etc/passwd

### **Task 5**
* [I'd prefer the first ones actually](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/5-firstlines)

While using the _head .._ command the script display the first 10 lines of /etc/passwd

### **Task 6**
* [Line #2](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/6-third_line)

While using the _head / tail .._ command the script display the third line of the file iacta .

The file iacta will be in the working directory

* You’re not allowed to use sed

_Note: The output will differ, depending on the content of the file iacta._

### **Task 7**
* [It is a good file that cuts iron without making a noise](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/7-file)

While using the _echo -e .._ command the script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

### **Task 8**
* [Save current state of directory](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/8-cwd_state)

While using the _ls -la_ command the script writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

### **Task 9**
* [Duplicate last line](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/9-duplicate_last_line)

While using the _tail .._ command the script duplicates the last line of the file iacta

* The file iacta will be in the working directory

### **Task 10**
* [No more javascript](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/10-no_more_js)

While using the _find .._ command the script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

### **Task 11**
* [Don't just count your directories, make your directories count](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/11-directories)

While using the _find .._ command the script counts the number of directories and sub-directories in the current directory.

* The current and parent directories should not be taken into account
* Hidden directories should be counted

### **Task 12**
* [What's new](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/12-newest_files)

While using the _ls .._ command the script displays the 10 newest files in the current directory.

Requirements:

* One file per line
* Sorted from the newest to the oldest

### **Task 13**
* [Being unique is better than being perfect](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/13-unique)

While using the _sort .._ command the script takes a list of words as input and prints only words that appear exactly once.

* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted

### **Task 14**
* [It must be in that file](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/14-findthatword)

While using the _grep .._ command the script display lines containing the pattern "root" from the file /etc/passwd

### **Task 15**
* [Count that word](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/15-countthatword)

While using the _grep .._ command the script display the number of lines that contain the pattern "bin" in the file /etc/passwd

### **Task 16**
* [What's next?](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/16-whatsnext)

While using the _grep .._ command the script display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd.

### **Task 17**
* [I hate bins](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/17-hidethisword)

While using the _grep .._ command the script display all the lines in the file /etc/passwd that do not contain the pattern "bin".

### **Task 18**
* [Letters only please](https://github.com/Aluranae/holbertonschool-shell/blob/main/io_redirections_and_filters/18-letteronly)

While using the _grep .._ command the script display all lines of the file /etc/ssh/sshd_config starting with a letter.

* include capital letters as well

