## 0-iam_betty
This script switches the current user to the user `betty` using the `su` command.
## 1-who_am_i
This script prints the effective username of the current user using the `whoami` command.
## 2-groups
This script prints all the groups the current user is part of using the `groups` command.
## 3-new_owner
This script changes the owner of the file `hello` to the user `betty` using the `chown` command.
## 4-empty
This script creates an empty file named `hello` using the `touch` command.
## 5-execute
This script adds execute permission to the owner of the file `hello` using `chmod u+x hello`.
## 6-multiple_permissions
This script adds execute permission to the owner and group, and read permission to others on the file `hello` using `chmod ug+x,o+r hello`.
## 7-everybody
This script adds execute permission to the owner, group, and others on the file `hello` using `chmod ugo+x hello` without commas.
## 8-James_Bond
This script sets the permissions of the file `hello` so that owner and group have no permissions, and others have all permissions, using numeric mode `chmod 007 hello`.
## 9-John_Doe
This script sets the permissions of the file `hello` to `-rwxr-x-wx` using `chmod 753 hello`.
