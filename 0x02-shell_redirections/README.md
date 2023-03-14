#!/bin/bash
Shell Script definitions

echo
allows user to display text
'< special character>\'
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
