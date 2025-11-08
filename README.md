File Explorer – Capstone Project
Overview

This is a console-based File Explorer developed in C++17.
It allows users to navigate directories, manage files, search for files, and view file information using simple text commands.
The project demonstrates practical use of the C++ <filesystem> library for handling file operations.

Features

List files and directories

Navigate through folders (cd, back)

Create, delete, rename, and copy files

Search files recursively

View file details (size, type, permissions, last modified)

Commands
Command	Description
list	Show files and folders in the current directory
cd <folder> / back	Change or go back a directory
create <file> / delete <file>	Manage files
rename <old> <new> / copy <src> <dest>	Rename or copy files
search <name>	Find files recursively
info <file>	Display file information
exit	Quit the explorer
How to Compile and Run
Windows or Linux:
g++ main.cpp -o explorer -std=c++17
./explorer

Example
> list
main.cpp
test.txt
README.md

> info main.cpp
Name: main.cpp
Size: 6081 bytes
Last Modified: Sat Nov 08 22:08:41 2025
Permissions: rw-rw-rw-

Author

Aditya Kumar
Capstone Project – Linux OS Track
Department of Computer Science and Engineering
