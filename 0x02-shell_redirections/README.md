#!/bin/bash
Shell Script definitions

echo
allows user to display text
0;276;0c'< special character>\'
allows you display a special character without running an error cause of syntax
cat <file>
allows you to display text that is in a file
tail <filename>
displays the last 10 lines of a file
head <filename>
displays the first 10 lines of a file

adding number flags to head and tail with a pipeline allows for us to find achieved number within a file

tail -1 iacta >> iacta
allows user to appendge the last line of the iacta file into the iacta file without overwriting it

find . -type d | wc -l
allows user to find directories and count how of them are there

ls -t | head
lists the 10 newest files within the current directory

sort | uniq -u
prints words that have only appeard once 

grep root /etc/passwd
search for any file assosciated with the word root and print it as output 

grep bin /etc/passwd | wc -l
counts thenumber of times the word bin has been displayed within /etc/passwd

grep root /etc/passwd | head -4 /etc/passwd
displays the files wih the words root and then shows the next 3 lines of files

grep -v(excluse a word flag) "bin" /etc/passwd
excludes word within selected directory

grep -i '^[a-z]' /etc/ssh/sshd_config
Used to display line of the file starting with a letter inclusive of capital letters

tr 'a' 'z' | tr 'c' 'e'
replacing certain letters within a string 

tr -d(deletes characters in set1 according to set2) "Cc"
deletes Cc when it is inputed

rev
aloows user to reverse any input they put in using echo 
