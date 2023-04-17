#Simple Shell

A simple UNIX command interpreter written in C.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Commands](#commands)
- [Built-in Commands](#built-in-commands)
- [Authors](#authors)

## Introduction

Simple Shell is a simple UNIX command interpreter that reads commands from either standard inpur or from a file, and execute them.

This program was written as part of a coding challenge on Ubuntu 20.04 LTS for ALX SE cohort 12 group project: simple\_shell, and may not be suitable for use in production enviroments.

##Getting Started

## Installation

To build the program, simple run the following commands:

This will build the `shell` executable.

To get started , clone the repository and compile the program using `gcc` compiler:

```bash
$ git clone https://github.com/Abasiifreke/simple_shell.git
$ cd simple_shell
$ gcc -Wall -Werror -Wextra -pedantric *.c -o shell
```

## Description

This program implements a basic shell in C language. It provides a simple command-line interface for the user to execute commands. The program reads input from the user and executes the command using the `execve` system call.

## Usage

To use the program, simply run the `shell` executable. The program will display a prompt and wait for user input. Enter a command and press enter to execute the command.

```bash
$ ./shell
```

You will be presneted with a prompt that looks like this:

```bash
(sh)$ 
```
You can then enter commands to execute, either one at a time, or multiple commands on the same line seperated by a semicolon;

```bash
(sh)$ ls
file.txt file2.txt file3.txt
(sh)$ pwd; ls
/home/user/simple_shell
file.txt file2.txt file3.txt
```

To exit
