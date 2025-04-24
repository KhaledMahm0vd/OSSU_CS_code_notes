Python for everybody

Charles Severance

  

A program:

- a sequence of stored instructions.

  

Generic Computer

![](file:///tmp/lu1422022dib.tmp/lu1422022dig_tmp_ce87b0cd.png)  

  

  

  

  

  

  

  

  

  

  

  

  

  

Definitions:

* Central Processing Unit:

runs the program – very dump but very very fast.

* Input Devices:

Keyboard, mouse, Touch screen.

* Output Devices:

Screen, speaker, printer, DVD burner.

* Main memory:

Fast small temp storage – lost on reboot – aka RAM.

* Secondary memory:

slower large permanent storage – lasts until deleted – disk drive / memory stick.

  

# Python as a Language:

python is created by Guido van Rossum

  

# Reserved Words:

* you can’t use reserved words as variable names / identifiers.

False class return is finally None if

for lambda continue True def from while

nonlocal and del global not with

as elif try or yield assert else import

pass break except in raise.

  

Sentence or lines:

x = 2 → assignment statement

x = x + 2 → Assignment with expression

print(x) → print statement.

  

X → variable, = → operator, 2 → constant, print-→ reserved word

  

  

Interactive versus Script:

* Interactive:

- you type directly to python one line at a time and it responds.

* Script:

- you enter a sequence of statements (lines) into a file using a text editor and tell python to execute the statements in the file.

  

Sequential steps:

* when a program is running, it flows from one step to the next. As programmers, we set up “paths” for the program to follow.

  

Repeated Steps:

program:

  

n = 5

while n > 0

print(n)

n = n – 1

print(“blastoff”)

  

loops (repeated steps) have iteration variables that change each time through a loop.

  

To automate writing and executing python files on Linux KDE desktop

ls → list directory files

kate 1.py

add **#!/usr/bin/python3** to the beginning of the file.

Add code and save the file

chmod +x file.py

./file.py

  

007-