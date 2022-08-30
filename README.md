# probable-enigma
### Important notes on Ethical Hacking and its pre-requisites


## Keyboard Shortcuts in Kali

| Command | Use |
| - | - |
| Ctrl alt T | Open new terminal |
| Ctrl + | Increase font on terminal |
| Ctrl - | Decrese font size on terminal |



## SYSTEM RELATED COMMANDS
| Command | Use |
| - | - |
| reboot | restart kali |
| halt | shutdown kali |



## DIRECTORY RELATED COMMANDS

| Command | Use |
| - | - |
| mkdir folderName | create a new folder |
| pwd | print working directory |
| ls | to list all the files and folder |
| ls -a | to list all hidden files |
|ls -l | to show all information like permissions, creation date for files |

### Note: ls commands can be clubbed like ls -la



## DIRECTORY NAVIGATION COMMANDS

| Command | Use |
| - | - |
| cd folderName | change directory / entry to the specified folder |
| cd .. | navigate one step back in directory |
| cd /root/Desktop/folder | open the speficied path folder in CLI |



## COPY / MOVE

| Command | Use |
| - | - |
| cp filename.txt /root/Desktop/ehe | copy filename.txt to foldername or path |
| mv filename.txt /root/Desktop/ehe | move filename.txt to foldername or path |



## PASSWORD RELATED STUFF

| Command | Use |
| - | - |
| sudo passwd root | change root password |




## FILE MANIPULATION

| Command | Use |
| - | - |
| touch fileName.txt | create a file |
| (vim/vi/nano) filename.txt | Use any one from the 3 to create a new file and open it in cli to enter text |
| :wq | write and quit from the above mentioned program |
| | |
| echo abc | prints abc on CLI |
| echo abc > filename.txt | writes abc to specified file (removes all the previously saved data) |
| echo abc >> filename.txt | writes abc to end of the specified file (if the file already exists and has data in it) |




## GITHUB RELATED / BASH FILES RELATED

| Command | Use |
| - | - |
| git clone <git repo link> | Clone repository from github |
| chmod +x filename.sh | to execute bash files first update permissions for the file using this command then execute |
| ./filename.sh | execute bash files |



## CLI HISTORY

| Command | Use |
| - | - |
| history | to view all the commands that have been executed on this terminal |
| !command number | to execute command present on that number in history |
| !! | to execute last command |
| uname | to show hostname on linux |
| uname -a | to show all system info |




## SYSTEM UPDATE
### To update kali to latest version run the following:
| Command | Use |
| - | - |
| apt-get update | downloads all required update files from trusted sources |
| apt-get upgrade | installs / applies all files to the Kali OS |


can also be done as apt-get update && apt-get upgrade
