A project on writing basic shell scripts
File name | Function
----------- | -------------------
**0-current_working_directory** | Prints the absolute path name of the current working directory
**1-listit** | Displays the contents list of your current directory
**2-bring_me_home** | Changes the working directory to the user's home directory
**3-listfiles** | Displays current directory contents in a long format
**4-listmorefiles** | Displays current directory contents, including hidden files (starting with `.`) using the long format.
**5-listfilesdigitonly** | Displays current directory contents using long format with user and group IDs displayed numerically and hidden files (starting with `.`)
**6-firstdirectory** | Creates a directory named `my_first_directory` in the `/tmp/` directory
**7-movethatfile** | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`
**8-firstdelete** | Deletes the file `betty`
**9-firstdirdeletion** | Deletes the directory `my_first_directory` that is in the `/tmp` directory
**10-back** | Changes the working directory to the previous one
**11-lists** | Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format
**12-file_type** | Prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run the script
**13-symbolic_link** | Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.
**14-copy_html** | Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
