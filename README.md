0-current_working_directory prints the absolute path name of the current working directory.
1-listit display the contents list of your current directory.
2-bring_me_home changes the working directory to the user’s home directory.
3-listfiles display current directory contents in a long format.
4-listmorefiles display current directory contents, including hidden files (starting with .). Use the long format.
5-listfilesdigitonly display current directory contents:
		     Long format
		     with user and group IDs displayed numerically
		     And hidden files (starting with .)
6-firstdirectory Create a script that creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile Move the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete Delete the file betty.
	      The file betty is in /tmp/my_first_directory
9-firstdirdeletion Delete the directory my_first_directory that is in the /tmp directory.
10-back  changes the working directory to the previous one.
11-lists lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14-copy_html copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
