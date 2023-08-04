---
layout: page
title: Mini Project 0
permalink: /mini-projects/mp0
parent: Mini Projects
nav_order: 1
---

# Mini Project 0 : Intro to System Calls
Welcome everyone to your very first Mini Project in Operating Systems & Networks Course. This Mini Project is designed to give you a basic introduction to system calls and to give you an idea of what and how you will be working with in the coming Mini Projects.
A system call is a routine that allows a user application to request actions that require special privileges. Adding system calls is one of several ways to extend the functions provided by the kernel.

## GitHub Classroom

For this project, follow [this link](https://r.mtdv.me/mp0) to accept the assignment. You should find a list of roll numbers already available as soon as you click on the link, ensure that you select your roll number correctly as that will mapped to your github id throughout the course. 
You will then be assigned a private repository on GitHub. This is where you will be working on the mini project. All relevant instructions regarding this project can be found below.   

> **Note:** If you are not familiar with git, please go through the [git tutorial](https://rogerdudler.github.io/git-guide/) before proceeding.
> **PS:** Your github id does not need to be with your college id, it can be with your personal email id as well.  

## Instructions

This Mini Project works as a basic introduction to system calls and to give you an idea of what you will be working with in the coming Mini Projects. It is **highly recommended to go through the Mini Project** to make the following Mini Projects easier.

## Part 1 - File Management

### Task

_Given a file, you need to reverse the contents of the file provided to you and store the result in a new file in directory named "Copies"._

Create a directory named "Copies" (if not already present), in the current directory with read, write and execute permissions. The new file created should be named "`<filename>`_reverse" and must have the same permissions as the original file.

**Note** that the file copied can be very LARGE (greater than RAM size). Your program should work in a reasonable amount of time (a minute at most) even for such large files.

```jsx
Input file : "newfile.txt" -> "This is a basic introduction to system calls."
Output file : "Copies/newfile_reverse.txt" -> 
              ".sllac metsys ot noitcudortni cisab a si sihT"

```

### Brief

In this task, you will be working with File Management system calls like open(), read() and write() to reverse the content of the file. As the file can be very LARGE, it’s impossible to load the entire file in RAM at once and hence it must be loaded in small parts. It is recommended to test your code with large files of at least a few GBs.

## Part 2 - Processes

### Task

Given a string of both uppercase and lowercase Latin letters, write a program to print string in lowercase in the parent process and in uppercase in the child process.

Note : Given string will only contain letters from Latin alphabet.

```jsx
Input String : "sOmeStrInGInPUT"
Output :
=== Parent Process ===
somestringinput
=== Child Process ===
SOMESTRINGINPUT

```

Note : The output of the child and parent process can be tangled (for example) :

```jsx
Input String : "sOmeStrInGInPUT"
Output :
=== Parent Process ===
=== Child Process ===
SOMESTRINGINPUT
somestringinput

```

### Brief

This task serves as an introduction to processes as well as system calls. Here, you will be working with the fork() system call which creates a new copy of the original running program. The new copy is called “child” while the original is called “parent”.

The two processes can be distinguished based on the return value of fork.

## Submission

The submission for this mini project will be through GitHub Classroom. The codebase will be automatically downloaded at the deadline, so ensure that everything is up in time. No exceptions will be granted.

Hard Deadline : 11:59 PM, 12th August 2023

The course policy regarding **late days is not applicable on Mini Project 0**.