What is shell?

A shell in a Linux operating system takes input from you in the form of commands, processes it, and then gives an output. It is the interface through which a user works on the programs, commands, and scripts. A shell is accessed by a terminal which runs it. 

What is shell scripting?

Shell scripting is writing a series of command for the shell to execute. It can combine lengthy and repetitive sequences of commands into a single and simple script, which can be stored and executed anytime. This reduces the effort required by the end user.

Creating a Shell Script 

1.Create a file using a vi editor(or any other editor).  Name  script file with extension .sh
2.Start the script with #! /bin/sh
3.Write some code.
4.Save the script file as filename.sh
5.For executing the script type bash filename.sh

Hisory command

history command is used to view the previously executed command. 
command syntax=$ history 

To show the limited number of commands that executed previously as follows: 
$ history 5

Head command

The head command, as the name implies, print the top N number of data of the given input. By default, it prints the first 10 lines
$ head state.txt

-n num: Prints the first ‘num’ lines instead of first 10 lines.
 $ head -n 5 state.txt

Tail command 

The tail command, as the name implies, print the last N number of data of the given input. By default it prints the last 10 lines 
$ tail state.txt

-n num: Prints the last ‘num’ lines instead of last 10 lines. 
$ tail -n 3 state.txt


