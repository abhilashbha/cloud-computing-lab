# Experiment 2 – C Compiler in Virtual Machine

## Aim

To install a C compiler in the virtual machine created using VirtualBox and execute a simple program.

## Environment

- VirtualBox
- Ubuntu virtual machine
- GCC compiler
- C language

## Procedure

1. Open VirtualBox.
2. Import the Ubuntu appliance (`ubuntu_gt6.ova`) if it is provided by the laboratory.
3. Start the Ubuntu virtual machine.
4. Open the terminal.
5. Navigate to the required working directory.
6. Create the C source file.
7. Compile the program using GCC.
8. Execute the generated program.

The laboratory manual uses the following workflow:

```bash
cd /opt/axis2/axis2-1.7.3/bin
gedit hello.c
gcc hello.c
./a.out
```

## Program

The repository contains `hello.c`, a simple C program that accepts two numbers and displays their addition.

## Result

The C program can be compiled using GCC and executed inside the Ubuntu virtual machine.

## Screenshots

Add actual terminal screenshots here when available.
