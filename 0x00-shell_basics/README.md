=====This Readme file describes what each sript in this directory does======

** The 0-current_working_directory script prints the absolute path name of the current working directory.

** The 1-listit script displays the contents list of your current directory.

** The 2-bring_me_home script changes the working directory to the user’s home directory.

** The 3-listfiles script displays current directory contents in a long format.

** The 4-listmorefiles script displays current directory contents, including hidden files (starting with .). Use the long format.

** The 5-listfilesdigitonly script displays current directory contents in Long format with user and group IDs displayed numerically and hidden files (starting with .).

** The 6-firstdirectory script creates a directory named my_first_directory in the /tmp/ directory.

** The 7-movethatfile script moves the file betty from /tmp/ to /tmp/my_first_directory.

** The 8-firstdelete script deletes the file betty from /tmp/my_first_directory.

** The 9-firstdirdeletion script deletes the directory my_first_directory that is in the /tmp directory.

** The 10-back script changes the working directory to the previous one.

** The 11-lists script lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

** The 12-file_type script prints the type of the file named iamafile that is inside the /tmp directory.

** The 13-symbolic_link script creates a symbolic link __ls__ in the current working directory to /bin/ls.

** The 14-copy_html script copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
	======Advanced Tasks======
** The 100-lets_move script moves all files in the current working directory that begins with an uppercase letter to the directory /tmp/u.

** The 101-clean_emacs script deletes all files in the current working directory that end with the character ~ .

** The 102-tree script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory using a two-space formatted command.

** The 103-commas script lists all the files and directories of the current directory, separated by commas (,) and the below format:
    Directory names end with a slash (/)
    Files and directories starting with a dot (.) are listed
    The listing is alpha ordered, except for the directories . and .. which are listed at the very beginning
    Only digits and letters are used to sort; Digits come first
    The listing ends with a new line
~
~
