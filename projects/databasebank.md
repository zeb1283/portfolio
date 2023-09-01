---
layout: project
type: project
image: img/bank-database-3d-render-icon-png.png
title: "Bank Database Emulation"
date: 2023
published: true
labels:
  - C++
  - C
  - gcc
  - Unix
  - VIM
  - g++
summary: "A small program that emulates a bank database using C and C++."
---

This project was completed in ICS 212, Program Structure. The user can add, find, remove, or delete records from the "database" that is stored on a .txt file.

Both programs use a linked list to hold the records, which consist of an Account Number, Name, and Address. This is all inputted by the user via the terminal. All project files were developed on a Unix server using the VIM text editor, and compiled using g++/gcc terminal commands and flags. These instructions are stored within a Makefile. In the C++ version, there is one for a "release" version and one for a "debug" version, which prints the parameters and function name whenever something within the program is called.

When programming both projects, I became painfully aware of how cautious you have to be when programming in certain languages. With the C project especially, it was important to clear the input buffer so I wouldn't get errors with scanf, and make sure that everything worked together perfectly to avoid the terrifying segfault. C++ was a better experience, as I was mostly able to adapt a lot of the code over, but getting a handle on classes, hierarchy, and passing by reference took a little bit of extra time.

Below is the class definition for the linked list that makes up the database in C++.

```cpp
#include "record.h"
#ifndef LLIST_H
#define LLIST_H

class llist
{
    private:
        record *    start;
        char        filename[20];
        int         readfile();
        int         writefile();
        void        cleanup();

    public:
        llist();
        llist(char[]);
        ~llist();
        void addRecord(int, char [ ],char [ ]);
        int findRecord(int);
        void printAllRecords();
        int deleteRecord(int);
};
#endif
```

The full project is stored on the [bank database repo](https://github.com/zeb1283/bankdatabase).
