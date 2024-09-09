## Lab 4
---
### Kernel
- A *Kernel* is the core of OS that controls and communicates with hardware resource.

### Shell
- A ***shell*** is a interface that allows users to communicate with kernel.  
Users run applications and give commands through shell.
---
### CLI(Command Line Interface) vs GUI(Graphic User Interface)
|  | CLI | GUI |
| ----- | ----- | -----|
| Should remeber commands | O | X |
| Mostly used | Keyboards | Mouse |
| Speed | Fast | Slow |
| Work method | automate tasks | manual labor |

---
### Shell command: pwd

***pwd*** shows the current path in a hierarchical directory

---
### Shell command: cd & ls
  
***cd*** changes directory

***ls*** lists files and directories.Li

#### Arguments

```
/                       root
.                       current directory
..                      upper-level directory
~                       home of current user
/[directory name]       absolute path
./[directory name]      relative path
../[directory name]     relative path
```
---
### options
- l show detailed information(long format)
- lh same as above, but size in units
---
### Manipulation:

***cp*** copy files and directories

***mv*** move files and directories or rename them

***rm*** delete files and directories *permantely and irreversevely*

***mkdir*** makes a new directory

***Wildcards***
| Pattern | Matches |
| ----- | ----- |
| * | All filenames |
| g* | All filenames that begin with the character "g" |
| b*.txt | All filenames that begin with the character "b" and end with the characters ".txt" |
| Data??? | Any filename that begins with the characters "Data" followed by exactly 3 more characters |

***'help'*** shows the documents included in the Git.  
You can get help when there is something you don't know while using git

***"man'*** is used to access the manual pages for other commands  

 ***"exit'*** is used to leave the manual page viewer (like less or more) and return to the command line.

