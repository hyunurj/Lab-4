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

#### ls
| Command | Result |
| ----- | ----- |
| ls | List the files in the working directory |
| ls/bin | List the files in the /bin directory (or any other directory we care to specify) |
| ls -1 | List the files in the working directory in long format |
| ls -1 / etc / bin | List the files in the /bin directory and the /etc directory in long format |
| ls -la .. | List all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format |

***'help'*** shows the documents included in the Git.  
You can get help when there is something you don't know while using git

***"man'*** is used to access the manual pages for other commands  

 ***"exit'*** is used to leave the manual page viewer (like less or more) and return to the command line.

