## Introduction

This project is a post-assignment for the operating systems course, and the project group consists of three individuals. The project implements some basic commands of a simple shell. Specifically, it includes commands like date, cat, `touch`, `mkdir`, `cp`, rm, mv, echo, cd, ls, and more. The "main" is the main entry point of the program. Running the executable file "main" will display a command prompt, prompting the user to input commands. Users can input commands as mentioned earlier and observe the corresponding results of their execution.

Within the SHELL directory, there is a subdirectory named "command," a C file "main.c" along with its executable file "main," and a README.md file. The "command" subdirectory contains the source code for some of the commands implemented in this project's shell. This "command" subdirectory further contains three subdirectories, each corresponding to the source code of a project member, as detailed in the documentation.

## Usage

The "main" file serves as the main entry point of the program.

When using the "mkdir" command to create a directory, it's necessary to explicitly specify that a directory is being created. For example: "mkdir dir1/;" or "mkdir /home/balaa/dir2".

The "rm" command must be used with the option "-rf", whether the file to be deleted is a regular file or a directory. For example: "rm -rf dir1/;" or "rm -rf file1".

When using the "mv" command to rename a directory, you still need to specify the directory to be renamed. For example: "mv dir1/ dir2/".