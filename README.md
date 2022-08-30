# probable-enigma
### Important notes on Ethical Hacking and its pre-requisites
Note structure: Command first then its meaning on next line

## Keyboard Shortcuts in Kali
### Ctrl alt T
Open new terminal
### Ctrl +
increase font size on terminal
### Ctrl -
decrease font size on terminal



## SYSTEM RELATED COMMANDS
### reboot
restart kali
### halt
shutdown kali



## DIRECTORY RELATED COMMANDS
### mkdir folderName
create a new folder
### pwd
print working directory
### ls
to list all the files and folder
### ls -a
to list all hidden files
### ls -l
to show all information like permissions, creation date for files
### Note: ls commands can be clubbed like ls -la



## DIRECTORY NAVIGATION COMMANDS
### cd foldername
change directory / enter to the specified folder
### cd ..
navigate one step back in directory
### cd /root/Desktop/folder
open the specified path folder in cli



## COPY / MOVE
### cp filename.txt /root/Desktop/ehe
copy filename.txt to foldername or path

### mv filename.txt /root/Desktop/ehe
move filename.txt to foldername or path:




## PASSWORD RELATED STUFF
### sudo passwd root
To change root password
### touch filename.txt
To create a file



## FILE MANIPULATION
### (vim/vi/nano) filename.txt
Use any one from the 3 to create a new file and open it in cli to enter text

### :wq
To write and quit from the above mentioned program 

### echo abc
prints abc on next line in cli

### echo abc > filename.txt
writes abc to specified file (removes all the previous data from the file)

### echo abc >>filename.txt
writes abc to end of the specified file(if it already exists and has data in it)



## GITHUB RELATED / BASH FILES RELATED
### How to clone repos from github:

git clone <git repo link>

### to execute .sh files first update permissions for the file then execute:

chmod +x filename.sh

./filename.sh



## CLI HISTORY
### history
to view all the commands that have been executed on this terminal

### !command number
to execute command present on that number in history

### !!
to execute last command

### uname
to show hostname on linux

### uname -a
to show all system info



## SYSTEM UPDATE
### To update kali to latest version run the following:
apt-get update

apt-get upgrade

can also be done as apt-get update && apt-get upgrade
