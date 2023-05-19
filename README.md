# alx-system_engineering-devops

some of the directories inside it are as follows:

## 0x00-shell_basics

### Looking Around

- What do the commands ls, less, file do
- How do you use options and arguments with commands
  \*Understand the ls long format and how to display it

### A Guided Tour

- What does the ln command do
- What do you find in the most common/important directories
- What is a symbolic link
- What is a hard link
- What is the difference between a hard link and a symbolic link

### Manipulating Files

- What do the commands cp, mv, rm, \* mkdir do
- What are wildcards and how do they work
- How to use wildcards
- Working with Commands
- What do type, which, help, man commands do
- What are the different kinds of commands
- What is an alias
- When do you use the command help instead of m

### Reading Man Pages

- How to read a man page
- What are man page sections
- What are the section numbers for User commands, System calls and Library functions

### Keyboard Shortcuts for Bash

- Common shortcuts for Bash

### LTS

- What does LTS mean?

## 0x01. Shell, permissions
### Resources
#### Read or watch:

### Permissions

#### man or help:
 - chmod
 - sudo
 - su
 - chown
 - chgrp
 - id
 - groups
 - whoami
 - adduser
 - useradd
 - addgroup

### Learning Objectives
At the end of this project, I am expected to be able to explain to anyone, without the help of Google:

#### Permissions
 - What do the commands chmod, sudo, su, chown, chgrp do
 - Linux file permissions
 - How to represent each of the three sets of permissions (owner, group, and other) as a single digit
 - How to change permissions, owner and group of a file
 - Why can’t a normal user chown a file
 - How to run a command with root privileges
 - How to change user ID or become superuser

#### Other Man Pages
 - How to create a user
 - How to create a group
 - How to print real and effective user and group IDs
 - How to print the groups a user is in
 - How to print the effective userid


## 0x02. Shell, I/O Redirections and filters
### man or help:

 - echo
 - cat
 - head
 - tail
 - find
 - wc
 - sort
 - uniq
 - grep
 - tr
 - rev
 - cut
 - passwd (5) (i.e. man 5 passwd)

### Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

#### Shell, I/O Redirection
 - What do the commands head, tail, find, wc, sort, uniq, grep, tr do
 - How to redirect standard output to a file
 - How to get standard input from a file instead of the keyboard
 - How to send the output from one program to the input of another program
 - How to combine commands and filters with redirections
 - Special Characters
 	- What are special characters
 - Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them
#### Other Man Pages
 - How to display a line of text
 - How to concatenate files and print on the standard output
 - How to reverse a string
 - How to remove sections from each line of files
 - What is the /etc/passwd file and what is its format
 - What is the /etc/shadow file and what is its format


## 0x03. Shell, init files, variables and expansions
### Resources
#### Read or watch:
 - Expansions
 - Shell Arithmetic
 - Variables
 - Shell initialization files
 - The alias Command
 - Technical Writing

#### man or help:
 - printenv
 - set
 - unset
 - export
 - alias
 - unalias
 - .
 - source
 - printf

### Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
 - What happens when you type $ ls -l *.txt

### Shell Initialization Files
 - What are the /etc/profile file and the /etc/profile.d directory
 - What is the ~/.bashrc file

### Variables
 - What is the difference between a local and a global variable
 - What is a reserved variable
 - How to create, update and delete shell variables
 - What are the roles of the following reserved variables: HOME, PATH, PS1
 - What are special parameters
 - What is the special parameter $??

### Expansions
 - What is expansion and how to use them
 - What is the difference between single and double quotes and how to use them properly
 - How to do command substitution with $() and backticks

### Shell Arithmetic
 - How to perform arithmetic operations with the shell

### The alias Command
 - How to create an alias
 - How to list aliases
 - How to temporarily disable an alias

### Other help pages
 - How to execute commands from a file in the current shell
