/*
 * Holt Bowmer
 * Simple C Shell
 * 2/27/14
 */


***She sells C shells down by the sea shore***

README:
This simple C shell program was a project for my Operating Systems class, my Junior year at Wake Forest. The purpose of the program was to demonstrate an understanding of the fork() and exec() calls and how they operate, particularly with an emphasis on the role the wait() function plays on process execution.

The program should prompt the user for an input, much like any bash or bourne shell would. This is not a highly sophisticated shell program, but it should be able to take in commands located in the usr/bin/ directory along with any additional parameters and execute the command successfully. By including an & at the end of the user string, the wait() command on the parent process will be removed, allowing the user command to run in the background while the program prompts the user for another command.

TO COMPILE: 
 * To compile lab3.c, simply enter the c-language compilation command "cc lab3.c"
 * Execute by entering the command "./a.out"
