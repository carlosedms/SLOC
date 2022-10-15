# Introduction

A simple program that counts the amount of code lines, empty lines and comment lines in a determined file or directory (or multiple directories, as the program is able to access them recursively if you wish to). Made as a project for Programming Language 1, and remade with improvements as a personal project.

Currently supported file types:

- C
- C header
- C++
- C++ header

# Running the program

The program receives as arguments the path to either a directory or a single file and displays a table with the contents of the analyzed files.

Some other arguments can be used to specify how the resulting table is sorted and if you want directories within the original to be scanned aswell.

To run the program, using a command prompt simply navigate to the directory in which the sloc executable is and run:

    sloc path-to-directory-or-file

For example:

To execute the program in an entire directory:

    sloc C:\Users\Carlos\Desktop\Programs\project_SLOC (path ends on a directory)

To execute the program on a single file:

    sloc C:\Users\Carlos\Desktop\Programs\project_SLOC\example.cpp (path ends on a file)

# Authors

Carlos Eduardo Miranda da Silva - cems2002@outlook.com - @carlosedms

Original code written in collaboration with:

William Campos Silva - camposwilliam23@gmail.com - @soueuwilliam
