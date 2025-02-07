# Shell, Permisssions

In this project I learned how permissions work in Shell through 16 tasks.

*However, here are the requirements that have been requested:*

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 22.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable

*Warning: tasks 3 / 13 / 14 / 15 / 16 must be done inside the sandbox in order to be corrected by the checker.*




# **What does it do?**

## **An explanation of how each script and permissions works**

### **Task 0**
* [My name is Betty](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/0-iam_betty)

While using the _su_ command the script switches the current user to the user betty.

* You should use exactly 8 characters for your command (+1 character for the new line)
* You can assume that the user betty will exist when we will run your script

### **Task 1**
* [Who am I](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/1-who_am_i)

While using the _whoami_ command the script prints the effective username of the current user.

### **Task 2**
* [Groups](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/2-groups)

While using the _groups_ command the script prints all the groups the current user is part of.

### **Task 3**
* [New owner](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/3-new_owner)

**The script must be present on the github repository and on the sandbox inside the folder /tmp**

While using the _chown_ command the script changes the owner of the file hello to the user betty.

### **Task 4**
* [Empty](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/4-empty)

While using the _touch_ command the script creates an empty file called hello.

### **Task 5**
* [Execute](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/5-execute)

While using the _chmod a_ command the script adds execute permission to the owner of the file hello.

* The file hello will be in the working directory

### **Task 6**
* [Multiple permissions](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/6-multiple_permissions)

While using the _chmod u/g/o x/r_ command the script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

* The file hello will be in the working directory

### **Task 7**
* [Everybody!](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/7-everybody)

While using the _chmod a_ command the script adds execution permission to the owner, the group owner and the other users, to the file hello.

* The file hello will be in the working directory
* You are not allowed to use commas for this script

### **Task 8**
* [James Bond](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/8-James_Bond)

While using the _chmod 0.._ command the script sets the permission to the file hello as follows:

* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions

The file hello will be in the working directory You are not allowed to use commas for this script

### **Task 9**
* [John Doe](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/9-John_Doe)

While using the _chmod 0.._ command the script sets the mode of the file hello to this:

* The file hello will be in the working directory
* You are not allowed to use commas for this script

### **Task 10**
* [Look in the mirror](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/10-mirror_permissions)

While using the _chmod --ref.._ command the script sets the mode of the file hello the same as olleh's mode.

* The file hello will be in the working directory
* The file olleh will be in the working directory

_Note: the mode of olleh will not always be 664. Make sure your script works for any mode._

### **Task 11**
* [Directories](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/11-directories_permissions)

While using the _chmod -R.._ command the script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

### **Task 12**
* [More directories](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/12-directory_permissions)

While using the _mkdir -m .._ command the script creates a directory called my_dir with permissions 751 in the working directory.

### **Task 13**
* [Change group](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/13-change_group)

While using the _chgrp .._ command the script changes the group owner to school for the file hello.

* The file hello will be in the working directory
* **The script must be present on the github repository and on the sandbox on the folder /tmp**

## **Task 14**
* [Owner and group](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/14-change_owner_and_group)

While using the _chown -R vincent:staff ./_ command the script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

* **The script must be present on the github repository and on the sandbox on the folder /tmp**

## **Task 15**
* [Symbolic links](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/15-symbolic_link_permissions)

While using the _chown -h .._ command the script changes the owner and the group owner of _hello to vincent and staff respectively.

* The file _hello is in the working directory
* The file _hello is a symbolic link

* **The script must be present on the github repository and on the sandbox on the folder /tmp**

## **Task 16**
* [If only](https://github.com/Aluranae/holbertonschool-shell/blob/main/permissions/16-if_only)

While using the _chown -from= .._ command the script changes the owner of the file hello to vincent only if it is owned by the user guillaume.

* The file hello will be in the working directory

* **The script must be present on the github repository and on the sandbox on the folder /tmp**