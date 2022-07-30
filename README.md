A simple C shell project

DESCRIPTION

This is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh)

INSTALLTION

Clone this repo into your working directory. Files should be compiled with GCC and the following flags: -Wall -Wextra -Werror -Pedaantic -Wno -Format

USAGE

After compliation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

INTERACTIVE MODE

In interactive mode, simply run the program and wait for the prompt to appear. from there, you can type commands freely, exiting with either the "exit" command or ctrl-D

NON-INTERACTIVE MODE

In non-interactive mode, echo your desired command and pipe it into the program like this:
	echo "ls"|./shell in non-interactive mode, the program will exit after finishing your desired commands(s)

FEATURES

1. Display a promt and wait for ther user to type a command.
A command-line always ends with a newline

2. The prompt is displayed again each time a command has beenexecuted

3. The command linesare simple, no semicolons, no pipes no redirections, or any other advanced features.

4. The command lines are made only of one word. No argument will be passed to the programs.

5. If an executable is not found the shell prints an error message and display the prompt again.

Credits

All codes written by Tlou Selolo and YOUR NAME
