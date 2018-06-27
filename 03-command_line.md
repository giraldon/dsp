# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> >

ls: list  
pwd: print working directory  
cd: change directory as arg  
..: go up one directory  
mkdir: make directory as arg  
touch: make file as arg  
ls -a,l,t: list hidden files, list long form, list in time order  
cp: copy arg into arg  
cp: copy multiple files as arg first into folder arg  
mv: move a folder or files as arg to directory arg  
mv: rename file arg to file arg  
rm: remove arg file or folder  
rm -r: remove arg folder and all children  
cat: output contents of file  
wc: output word count of file  
sort: sort lines of text   
uniq: remove duplicate lines  
grep: find  
sed: find and replace  
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 

ls: list all files and folders in working directory  
ls -a: list all files and folders including hidden  
ls -l: list all files and folders in long form as a table  
ls -lh: list all files and folders in long form, in human readable format  
ls -lah: list all files and folders, including hidden, in long table form and human readable format  
ls -t: list all files and folders in order of last modified  
ls -Glp: list all files and folders, inhibiting display of group information, append filetype indicator to files  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 

-o: long format without group name  
-x: display files as rows across the screen  
-d: display directories only  
-c: display files by timestamp  
-b: display nonprinting characters in octal  


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> >  
 
xargs changes input from an argument to a command.  

you could use it to make multiple folders with different names with one command  

echo "documents pictures videos" | xargs mkdir  

you could also use it to find certain files or folders and make changes to them all at once  
