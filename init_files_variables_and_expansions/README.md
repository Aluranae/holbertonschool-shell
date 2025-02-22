# Shell, init files, variables and expansions

In this project I learned how init files, variables and expansions work in Shell through 18 tasks

*However, here are the requirements that have been requested:*

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use &&, || or ;
* You are not allowed to use bc, sed or awk
* All your files must be executable


# **What does it do?**
## **An explanation of how each script works**




### **Task 0**
* [Alias](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/0-alias)

While using the _echo .._ command the script that creates an alias.

* Name: ls
* Value: rm *

### **Task 1**
* [Hello you](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/1-hello_you)

While using the _echo .._ prints hello user, where user is the current Linux user.

### **Task 2**
* [The path to success is to take massive, determined action](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/2-path)

While using the _export .._ the script add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

### **Task 3**
* [If the path be beautiful, let us not ask where it leads](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/3-paths)

While using the _echo .._ the script counts the number of directories in the PATH.

### **Task 4**
* [Global variables](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/4-global_variables)

While using the _printe .._ command the script lists environment variables.

### **Task 5**
* [Local variables](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/5-local_variables)

While using the _set .._ command the script lists all local variables and environment variables, and functions.

### **Task 6**
* [Local variable](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/6-create_local_variable)

While using the _varname=value_ command the script creates a new local variable.

### **Task 7**
* [Global variable](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/7-create_global_variable)

While using the _export .._ command the script creates a new global variable.

### **Task 8**
* [Every addition to true knowledge is an addition to human power](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/8-true_knowledge)

While using the _export .._ command the script  prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

### **Task 9**
* [Divide and rule](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/9-divide_and_rule)

While using the _echo .._ command the script prints the result of POWER divided by DIVIDE, followed by a new line.

* POWER and DIVIDE are environment variables

### **Task 10**
* [Love is anterior to life, posterior to death, initial of creation, and the exponent of breath](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/10-love_exponent_breath)

While using the _echo .._ command the script displays the result of BREATH to the power LOVE

* BREATH and LOVE are environment variables
* The script should display the result, followed by a new line

### **Task 11**
* [There are 10 types of people in the world -- Those who understand binary, and those who don't](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/11-binary_to_decimal)

While using the _echo .._ command the script dconverts a number from base 2 to base 10.

* The number in base 2 is stored in the environment variable BINARY
* The script should display the number in base 10, followed by a new line

### **Task 12**
* [Combination](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/12-combinations)

While using the _echo .._ command the script prints all possible combinations of two letters, except oo.

* Letters are lower cases, from a to z
* One combination per line
* The output should be alpha ordered, starting with aa
* Do not print oo
* Your script file should contain maximum 64 characters

### **Task 13**
* [13. Floats](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/13-print_float)

While using the _printf .._ command the script prints a number with two decimal places, followed by a new line.
The number will be stored in the environment variable NUM.

### **Task 14**
* [Decimal to Hexadecimal](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/14-decimal_to_hexadecimal)

While using the _printf .._ command the script converts a number from base 10 to base 16.

* The number in base 10 is stored in the environment variable DECIMAL
* The script should display the number in base 16, followed by a new line


## Advanced Tasks


### **Task 15**
* [What happens when you type ls *.c](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/18)

Write a blog post describing step by step what happens when you type ls *.c and hit Enter in your shell. Try to explain every step you know of, and give examples. A total beginner should understand what you have written.

* Have at least one picture, at the top of the blog post
* Publish your blog post on Medium or LinkedIn
* Share your blog post at least on LinkedIn
* Write professionally and intelligibly
+ Please, remember that these blogs must be written in English to further your technical ability in a variety of settings

_**Remember, future employers will see your articles; take this seriously, and produce something that will be an asset to your future.**_

* [Linkedin](https://www.linkedin.com/posts/benjamin-estrada-880b06297_this-article-is-the-result-of-one-of-the-activity-7294838079356358656-WI4x?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEfjoWABQhDobpxQG_X41v8grgLc1NtVwLc)
* [Medium]

When done, please add all urls below (blog post, LinkedIn post, etc.)

### **Task 16**
* [Everyone is a proponent of strong encryption](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/15-rot13)

While using the _tr .._ command the script encodes and decodes text using the rot13 encryption. Assume ASCII.

### **Task 17**
* [The eggs of the brood need to be an odd number](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/16-odd)

While using the _paste .._ command the script prints every other line from the input, starting with the first line.

### **Task 18**
* [I'm an instant star. Just add water and stir.](https://github.com/Aluranae/holbertonschool-shell/tree/main/init_files_variables_and_expansions/17-water_and_stir)

While using the _printf .._ command the script adds the two numbers stored in the environment variables WATER and STIR and prints the result.

* WATER is in base water
* STIR is in base stir.
* The result should be in base bestchol
