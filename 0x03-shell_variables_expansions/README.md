#Shell Scripting Work

#Descriptions of the commands used in project

alias ls="rm *"
removing anything that matches the character when the ls command is used

echo "hello $USER"
prints a string that greets a user

PATH=$PATH:/action
adding a pathname to an existing path

echo $PATH | tr ':' 'n' | wc -l
1. We needed to print directory files for $PATH
2. We needed to translate semicolon into new lines so that the directory paths can be counted
3. USe the wc -l to count the output of previous command

printenv
printing global variable

set
printing local variable

BEST="School"
Creates a variable

export BEST="School"
Want to make local variable a global variable

echo $((TRUEKNOWLEDGE+128))
calculationg a sum

echo {a..z}{z..a} | tr '' '\n' | grep -v "oo"
1. printing both combos of the alphabet
2. translate blackspaces and inserting new lines for each blankspace
3. excluding any variation of oo
