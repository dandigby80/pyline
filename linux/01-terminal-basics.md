## Getting Comfortable with the Terminal:

## Learning Goals:

* Understand what the terminal is and how to interact with it
* Learn basic navigation and file operations

## What is the 'Terminal' and how do we interact with it?

The terminal in linux is a text-based software interface that allow us to interact with the linux system by entering text commands at the command prompt (it can sometimes be referred to as the command line or console). It is used to execute commands that allow us to control the systems processes and manage files. It is very efficient because it uses a text based interface that has deep control over the operating system. The terminal is only part of the system though. To process what we enter into the terminal we need another program to process these commands, this is called the 'shell'.

## What is the 'Shell' and how does the terminal interact with it?

The shell in linux is a piece of software that takes a users commands from the terminal, interprets them and passes them onto the kernel. Its main jobs are to: 

* Take the command from the user
* Check to make sure it is a valid command and the syntax is correct
* Convert it into a form the kernel can understand and passes it along to the kernel to process

## What is the 'Kernel' and how does it process our commands?

The kernel is a program that sits at the core of the Linux Operating System that co-ordinates the interaction of software and hardware. The kernel handles things such as process management, memory management, drivers and various system duties to ensure the error free running of the system. We can interact with the kernel directly through commands written in the terminal that are translated and passed to the kernel through the shell.

So our interaction with the kernel starts first with commands we enter using our keyboard in the terminal which are then translated by the shell and passed down to the kernel which then takes those translated commands and acts upon them to make changes to the Linux system. Powerful when you think about it!

## Navigation and File Operations:

### Understanding the File System Hierarchy:

The file system hierarchy or sometimes called the file system tree is the method in which a unix-like system organises its files and directories. The first directory in the file system is the 'root' directory. Every other file or directory branches out from the root directory (hence the 'tree' name). Linux also has a single file system tree - all storage devices are mounted at various points on the tree where the user chooses, they don't have separate file trees like a windows based system.

When we begin a linux system we are always at our home directory. From here we can traverse the tree into any directory or sub-directory at our will. At any point on the tree we are always inside a directory, wether it be our home directory or some other directory - we will always be in a directory which is called the 'current working directory'. The linux system can contain hundreds of directories so we need to know where we are on the tree quickly - this where our first command comes in handy - 'print working directory'.

- pwd - print working directory

When we log into a linux system we are usually placed in our home directory, this is the only place a normal user can make changes or save and delete files. Now we know we are in a directory and we can use the 'pwd' command to print the working directory we are in, we would now like to know what is inside that directory. This is where the 'ls' command comes in handy. The 'ls' command lists all the files and directories in the current working directory.

- ls - list (or list storage)

Ok, so we know which directory we are in and what is inside that directory - how do we move around and go into another directory? That is where the 'cd' command comes in. 'cd' is change directory and we can use this and then the name of the directory to jump into that directory.

- cd - change directory
