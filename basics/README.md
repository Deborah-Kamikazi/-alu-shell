0 current working directory prints the current working directory
1-listit - Lists the contents of the current directory.
2-bring_me_home - Changes the current working directory to the user's home directory using cd ~
3-listfiles - Displays the contents of the current directory in long listing format using ls -l
4-listmorefiles - Lists all contents of the current directory (including hidden files) in long format using ls -la
5-listfilesdigitonly - Lists all contents (including hidden files) in long format with numeric user and group IDs using ls -lan
6-firstdirectory - Creates a directory named my_first_directory inside /tmp/ using mkdir.
7-movethatfile - Moves the file betty from /tmp/ to /tmp/my_first_directory/ using mv.
8-firstdelete - Deletes the file betty from /tmp/my_first_directory using rm.
9-firstdirdeletion - Removes the empty directory /tmp/my_first_directory using rmdir.
10-back - Changes the working directory to the previous one using cd -.
11-lists - Lists all files (including hidden) in current, parent, and /boot directories in long format using ls -la . .. /boot.
12-file_type - Uses the file command to print the type of /tmp/iamafile.
13-symbolic_link - Creates a symbolic link named __ls__ in the current directory pointing to /bin/ls.
14-copy_html - Copies .html files from the current directory to the parent directory, only if they are newer or do not exist in the parent directory, using cp -u
15-lets_move - Moves all files starting with uppercase letters from the current directory to /tmp/u
16-clean_emacs - Deletes all files ending with ~ in the current directory using rm *~.
17-tree - Creates nested directories welcome/, welcome/to/, and welcome/to/school/ using mkdir -p welcome/to/school.
