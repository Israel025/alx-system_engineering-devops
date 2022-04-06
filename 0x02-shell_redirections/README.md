** The 0-hello_world script prints “Hello, World”, followed by a new line to the standard output.

** The 1-confused_smiley script displays a confused smiley "(Ôo)'.

** The 2-hellofile script displays the content of the /etc/passwd file.

** The 3-twofiles script displays the content of /etc/passwd and /etc/hosts.

** The 4-lastlines script displays the last 10 lines of /etc/passwd.

** The 5-firstlines script displays the first 10 lines of /etc/passwd.

** The 6-third_line script displays the third line of the file iacta.

** The 7-file script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

** The 8-cwd_state script writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

** The 9-duplicate_last_line script duplicates the last line of the file iacta.

** The 10-no_more_js script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

** The 11-directories script counts the number of directories and sub-directories in the current directory. The current and parent directories are not taken into account and Hidden directories are not counted.

** The 12-newest_files script displays the 10 newest files in the current directory.

** The 13-unique script takes a list of words as input and prints only words that appear exactly once.
    Input format: One line, one word
    Output format: One line, one word
    Words are sorted.

** The 14-findthatword script display lines containing the pattern “root” from the file /etc/passwd.

** The 15-countthatword script display the number of lines that contain the pattern “bin” in the file /etc/passwd.

** The 16-whatsnext script display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

** The 17-hidethisword script display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

** The 18-letteronly script display all lines of the file /etc/ssh/sshd_config starting with a letter. including capital letters as well.

** The 19-AZ script replaces all characters A and c from input to Z and e respectively.

** The 20-hiago script removes all letters c and C from input.

** The 21-reverse script reverse its input.

** The 22-users_and_homes script displays all users and their home directories, sorted by users based on the the /etc/passwd file.

==========================ADVANCED TASKS===========================================
===================================================================================
** The 100-empty_casks script finds all empty files and directories in the current directory and all sub-directories.

    Only the names of the files and directories would be displayed (not the entire path)
    Hidden files would be listed
    One file name per line
    The listing ends with a new line.

** The 101-gifs script lists all the files with a .gif extension in the current directory and all its sub-directories.
    Hidden files will be listed
    Only regular files (not directories) will be listed
    The names of the files will be displayed without their extensions
    The files will be sorted by byte values, but case-insensitive (file aaa will be listed before file bbb, file .b will be listed before file a, and file Rona will be listed after file jay)
    One file name per line
    The listing will end with a new line
    without the use of basename, grep, egrep, fgrep or rgrep commands.



