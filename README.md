EDIT:
	This is my original readme, but man this code is MESSY. I can see myself going back and rewriting this to be
	more clear in the future but for now I will frame this as my headspace from sophmore year of college in 2019.
	I unfortunately do not think this is the final version of this project, I think I lost that code on my college's
	server. However, this is fairly close. I apologize for any bugs. (I recall being proud that my implementation
	didn't lock up in some insane corner cases where the official linux one did.)

NAME
	smash - command shell based upon the linux version of the name "bash".

SYNOPSIS
	smash

DESCRIPTION
	Enter in commands to accomodate the following options.

	No arguments neccessary unless the specific command requires them to meet the desired result.

	Smash now supports all forms of IO redirection and partial signal handling.
	
	exit - smash supports the exit command to immediately stop all functionality of the program.

	history [NumberOfPriorEntries] 
	Smash stores up to 10 history entries of previous commands at once. You can access
	all previous listings by simply using the history command, or retrieve a specified 
	amount by entering a value.

	cd [DirectoryNameOrPath]
	Smash is able to natively change the current working directory by specifying the 
	one you would like to change to.

	external commands - smash supports execution of all external commands provided by
	your specific operating system in the $PATH section. Arguments may vary so please
	consult the specific command parameters with "man command" to get more information.

	Exit Statuses - Smash provides an exit status of 0 for a succesfully complete command,
	1 for a native command failure, 2 for an external command failure, and 127 for an
	unrecognized external command.

	BUGFIXES: Fixed error with memory not being freed upon execution of blank command.

AUTHOR
	Written by Jared Lytle.
