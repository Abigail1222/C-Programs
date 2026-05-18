# Banking Queue Management System (C)

A console-based banking queue management system developed in C as an academic project.  
The program simulates customer ticket generation and queue handling for different banking services using dynamic linked lists.

## Features

- Ticket creation system
- Multiple queue categories:
  - Fast service queue
  - Standard service queue
  - Executive assistance queue
- Queue visualization in console
- Ticket removal and queue updates
- Ticket service time tracking
- Basic file logging (`turno.txt`)
- Console-based bank terminal simulation

## Technologies & Concepts

- C Programming Language
- Dynamic memory management
- Linked lists
- Pointers and structs
- Console-based UI
- File handling
- Queue simulation logic

## Project Structure

```txt
.
├── main.c
├── turno.txt
└── README.md
```

## Platform Notes

This project was originally developed for Windows and relies on Windows-specific console libraries such as:

```c
#include <windows.h>
```

Because of this, the project may require modifications to compile and run on macOS or Linux systems.

Some Windows-specific functions used include:

- `SetConsoleCursorPosition`
- `SetConsoleTextAttribute`
- `system("cls")`
- `getch()`
- `itoa()`

## Compilation (Windows)

Using GCC / MinGW:

```bash
gcc main.c -o banking_queue_system.exe
```

## Running the Program

```bash
./banking_queue_system.exe
```

## Possible Future Improvements

- Cross-platform compatibility
- Refactoring console UI
- Safer input handling
- Modular file structure
- Persistent database storage
- GUI implementation

## Learning Outcomes

This project helped me practice:

- Manual memory management in C
- Dynamic data structures
- Queue handling logic
- File operations
- Console application development
- Program organization and procedural design


Academic project created several years ago and preserved as part of my programming portfolio.
