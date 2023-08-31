---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Bank Database Emulation in C++"
date: 2023
published: true
labels:
  - C++
  - Unix
  - VIM
  - g++
summary: "A small program that emulates a bank database using C++."
---

This project was completed in ICS 212, program structure. The user can add, find, remove, or delete records from the "database" that is stored on a .txt file.

The program uses a linked list to hold the records, which consist of an Account Number, Name, and Address. This is all inputted by the user via the terminal. All project files were developed on a Unix server using the VIM text editor, and compiled using g++ terminal commands and flags. These instructions are stored within 2 Makefiles, one for a "release" version and one for a "debug" version, which prints the parameters and function name whenever something within the program is called.

Below is the class definition for the linked list that makes up the database.

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
