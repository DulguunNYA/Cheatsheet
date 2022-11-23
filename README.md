# Cheatsheet

````  
cd ~
````  
go to home

````  
mv [OBJECT] [NEW_LOCATION]
````
Relocate a file in another folder
````
mv
````
can change name

````
less [OBJECT]
````
Read a file
````
help / man
````
find help
````
rm  [OBJECTS]
````
to delet/remove a file
````
mkdir [object]
````
command to create
````
sudo [COMMAND][OBJECT]
````
do a command as an admin
````
grep [WORD] [ITEM]
````
search a word in an item
````
cp [ITEM][NEW_ITEM]
````
copy an item to creat another item
# RTFM - Read the Frickin' Manual

````
man [ITEM]
````
man opens the manual fot the wanted page and although it can be technical it remains one of the best place for information.  
````
whatis [ITEM]
````
if you simply want a description let's try to use whatis.

````
pwd [ITEM]
````
shows where u are

# Navigation

````
pushd [ITEM]
````
The pushd command saves the current working directory in memory so it can be returned to at any time, pushd moves to the parent directory.

````
popd
````
The popd command returns to the path at the top of the directory stack.
# File Operation
````
echo "ITEM" > FILESNAME
````
help's u to write in a file

# Permission

````
sudo
````
If you prefix “sudo” with any command, it will run that command with elevated privileges or in other words allow a user with proper permissions to execute a command as another user, such as the superuser.

`````
chmod
`````
Chmod takes three main arguments: r, w, and x, which stand for read, write, and execute, respectively. Adding or removing combinations of the arguments controls file and folder permissions. For example, chmod +rwx adds permission to read, write, and execute scripts. Running chmod -wx removes the ability to write and execute.
````
chown [OPTIONS] USER[:GROUP] FILE(s)
````
The chown command allows you to change the user and/or group ownership of a given file, directory, or symbolic link.

````
ls -l filename.txt
````
**output**

-rw-r--r-- 12 linuxize users 12.0K Apr  8 20:51 filename.txt  
|[-][-][-]-   [------] [---]
                |       |
                |       +-----------> Group
                +-------------------> Owner


````
chgrp
`````
The chgrp (change group) command alters the group name that a file or directory belongs to.  

# Environment variables

````
env
````
If env is run without any options, it prints the variables of the current environment.

````
printenv
````
The printenv command-line utility displays the values of environment variables in the current shell.

We can specify one or more variable names on the command line to print only those specific variables. Or, if we run the command without arguments, it will display all environment variables of the current shell.

````
set
````
The set command is a built-in Linux shell command that displays and sets the names and values of shell and Linux environment variables.

````
unset
````
Use the unset command to delete the variables during program execution. It can remove both functions and shell variables. Using the unset command, you can unset values and attributes of shell variables and functions.
````
export
````
It is used to mark variables and functions to be passed to child processes. Basically, a variable will be included in child process environments without affecting other environments. 
