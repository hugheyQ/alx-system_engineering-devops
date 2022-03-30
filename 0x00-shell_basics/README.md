# Description of Scripts
The following is a writeup of the various scripts available in this directory.

## 0-Current working directory
A script that prints the absolute path name of the current working directory.

## 1-Listit
A script displaying the contents of your current directory.

## 2-Bring me home
A script that changes the working directory to the user's home directory.

## 3-Listfiles
A script that displays directory contents in a long format.

## 4-Listmorefiles
A script that displays the current directory's contents, including hidden files (starting with .) while using the long format.

## 5-Listfilesdigitonly
A script that displays the current directory's contents in long format, with user and group IDs displayed numerically and hidden files(starting with .).

## 6-Firstdirectory
A script that creates a directory named my_first_directory in the /tmp/ directory.

## 7-Movethatfile
A script that moves the file betty from /tmp/ to /tmp/my_first_directory.

## 8-Firstdelete
A script that deletes the file betty.

## 9-Firstdirdeletion
A script that deletes the directory my_first_directory that is in the /tmp directory.

## 10-Back
A script that changes the working directory to the previous one.

## 11-Lists
A script that lists all files (even ones with names beginning with a period character, which are normaly hidden) in the current directory and the parent of the working directory and the /boot directory(in this order), in long format.

## 12-Filetype
A script that prints the type of the file named iamafile.

## 13-Symboliclink
A script that creates a symbolic link to /bin/ls, named __ls__.

## 14-Copyhtml
A script that copies all the HTML files form the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

## 15-Letsmove
A script that moves all files beginning with an uppercase letter to the directory /tmp/u.

## 16-Cleanemacs
A script that deletes all files in the current working directory that end with the character ~.

## 102-tree
A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

## 103-commas
A script that lists all the files and directories of the current directory, seperated by commas (,).
- Directory names end with a slash
- Files and directories starting with a dot (.) are listed
- The listing is alpha ordered, except for the directories . and .. which are listed at the very beginning.
- Only digits and letters are used to sort; Digits come first.

## school.mgc
A magic file that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

