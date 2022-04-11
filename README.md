# File-System-Manager-with-Shell

The purpose of these programs is to simulate a file system manager within a shell.


Within the shell the following commands can be perfromed:


ls : This command will list out all the files in the current directory.

ls -a : This command will list out all the files in the current directory, including the hidden ones.

id : This command will find the names of user, group names and numeric IDs.

pwd : This command will print out the full path of the current directory that the user is currently on.

cat : This command will print the content of a file.

exit : This command will exit the shell.

clear : This command will clear the shell of text.

echo : This command prints out arguments as standard output.

whoami : This command prints out the current user’s name.

df: This command will show the user both th free and used disk space of the file system.



Within the file system manager the following commands can be performed:
root: initilizes the root dir

print: prints working directory 

mkdir: sub-directory creation

rmdir: deletion

mvdir: rename directory

szfil: resize

chdir: changes current directory working

exit: end the prog



First program to be run is Myshell.c 

To run and compile:

Have the Myshell.c code

In the terminal: gcc Mshell.c then ./a.out

Now the command line should be running, showing NEW_SHELL

Once the shell is running open the file system manager:

To run and compile:

Have the Filemanager.c code

In the terminal: gcc -o fs Filemanager.c && ./fs

To exit the file manager type exit and enter

To exit the NEW_SHELL ctrl+c
