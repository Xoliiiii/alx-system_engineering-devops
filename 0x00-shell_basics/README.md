#!/bin/bash

realpath - indicates path name of current working directory
ls- lists contents of your current directory
pwd- prints the working directory thaat you are currently working on
ls -l- provides a long formated list of files that are within directory
cd /root - return user to home directory
ls -al - list all files (hidden included) in long format
mkdir /tmp/my_first_directory - created a directory in a different root
mv /tmp/betty /tmp/my_first_directory - moved betty file to a different directory
rm /tmp/my_first_directory/betty - deletes betty files in its current directory
rmdir /tmp/my_first_directory - deltes entire directory in the tmp directory
cd - - retuen userto previous working directory
file <filename> - indicates what typeof file it is
ln -s /bin/ls(target) __ls__(target name) - creates a symbolic link for desired target with desired target name in directory
