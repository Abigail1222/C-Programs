# Legacy C Console Applications

This repository contains two console-based applications developed in C several years ago as academic/personal programming projects.

Both applications were originally built for Windows using `windows.h` console utilities and are preserved as part of my programming portfolio.

---

# Projects Included

## 1. Banking Queue Management System

A console application that simulates a banking ticket and queue management system using dynamic linked lists.

### Features

- Ticket generation system
- Multiple queue categories:
  - Fast service queue
  - Standard service queue
  - Executive assistance queue
- Queue visualization in console
- Ticket removal handling
- Waiting time tracking
- Basic file logging
- Console-based banking terminal simulation

### Concepts Used

- Linked lists
- Dynamic memory management
- Queue logic
- File handling
- Structs and pointers
- Console UI programming

---

## 2. Student/Personal Record Management Form System

A console-based CRUD-style form management system designed to store and manage personal records.

### Features

- Record registration (`Alta`)
- Record deletion (`Baja`)
- Record modification (`Cambio`)
- Record search (`Detecta`)
- Full report generation
- Alphabetical sorting
- Validation system for user input
- File persistence using `.txt` files

### Stored Information

- CURP
- Full name
- Address information
- Birth date
- Gender
- Age
- Tutor information

### Concepts Used

- Struct nesting
- Data validation
- File handling
- CRUD operations
- Sorting algorithms
- Console interaction
- Procedural programming in C

---

# Technologies

- C Programming Language
- Windows console libraries (`windows.h`)
- Dynamic memory management
- File I/O
- Console-based interfaces

---

# Repository Structure

```txt
.
├── FORMULARIO PIA - COPY/
│   ├── FORMULARIO PIA 1.3.c
│   └── FORMULARIO PIA 1.3.exe
│
├── PIA EST/
│   ├── PIA CON ARCHIVOS_1.c
│   ├── PIA CON ARCHIVOS_1.exe
│   
│
└── README.md
```

---

# Platform Notes

These projects were originally developed for Windows and use Windows-specific console functionality such as:

```c
#include <windows.h>
```

Functions used include:

- `SetConsoleCursorPosition`
- `SetConsoleTextAttribute`
- `system("cls")`
- `getch()`
- `itoa()`

Because of this, additional modifications may be required to compile and run the projects on macOS or Linux systems.

---

# Notes

- Source code comments are primarily written in Spanish.
- These projects are preserved mostly in their original state.
- They represent some of my early experience working with low-level programming concepts in C.

---

# Learning Outcomes

Through these projects, I practiced:

- Manual memory management
- Dynamic data structures
- Procedural software design
- File persistence
- Input validation
- Console application development
- Program organization in C

---

# Future Improvements

Possible future updates include:

- Cross-platform compatibility
- Safer input handling
- Refactoring into modular architecture
- Improved documentation
- GUI implementations
- Modern C standards compatibility

---

Academic/personal projects preserved as part of my software development portfolio.
