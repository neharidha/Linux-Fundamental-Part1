# Linux-Fundamental-Part1


Linux fundamentals Part 1 | TryHackMe | Solution

Module — Linux Fundamentals

Linux Fundamentals Part 1

Embark on the journey of learning the fundamentals of Linux. Learn to run some of the first essential commands on an interactive terminal

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

echo	Output any text that we provide
whoami	Find out what user we're currently logged in as!
ls	listing
cd	change directory
cat	concatenate
pwd	print working directory
Search for file:find, grep

&	 This operator allows you to run commands in the background of your terminal.

&&	This operator allows you to combine multiple commands together in one line of your terminal.

(>)	This operator is a redirector - meaning that we can take the output from a command (such as using cat to output a file) and direct it elsewhere.

(>>)	This operator does the same function of the > operator but appends the output rather than replacing (meaning nothing is overwritten).
— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —
— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —
— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task1

Let’s get started!

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task2

Research: What year was the first release of a Linux operating system?

Correct Answer: 1991

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task3
I’ve deployed my first Linux machine!

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task4

If we wanted to output the text “TryHackMe”, what would our command be?

Correct Answer: echo TryHackMe

What is the username of who you’re logged in as on your deployed Linux machine?

Correct Answer: tryhackme

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task5

On the Linux machine that you deploy, how many folders are there?

Correct Answer: 4

Which directory contains a file?

Correct Answer:folder4

What is the contents of this file?

Correct Answer: hello world

Use the cd command to navigate to this file and find out the new current working directory. What is the path?

Correct Answer: /home/tryhackme/folder4

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task6

Use grep on “access.log” to find the flag that has a prefix of “THM”. What is the flag?

Correct Answer: THM{ACCESS}

And I still haven’t found what I’m looking for!

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task7

If we wanted to run a command in the background, what operator would we want to use?

Correct Answer: &

If I wanted to replace the contents of a file named “passwords” with the word “password123”, what would my command be?

Correct Answer: echo password123 > passwords

Now if I wanted to add “tryhackme” to this file named “passwords” but also keep “passwords123”, what would my command be

Correct Answer: echo tryhackme >> passwords

Now use the deployed Linux machine to put these into practice

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task8

I’ll have a play around!

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task9

Terminate the machine deployed in this room from task 3.

Correct Answer: No answer needed

Join Linux Fundamentals Part 2!

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —
