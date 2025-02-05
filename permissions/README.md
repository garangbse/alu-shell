0-iam_betty
This command uses su (substitute user) to switch to the user "betty".

1-who_am_i
The script uses the whoami command to retrieve and print the effective username of the current user.

2-groups
The script uses the groups command to print all the groups the current user is a member of.

3-new_owner
The script uses the chown command to change the ownership of the file hello to the user betty.

4-empty
The script uses the touch command to create an empty file called hello if it doesn't already exist.

5-execute
The script uses the chmod command to add execute (x) permission for the user (owner) of the file hello in the current directory.

6-multiple_permissions
ug+x adds execute permission to both the user (owner) and group owner.
o+r adds read permission to other users.
making chmod ug+x,o+r hello that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7-everybody
u+x adds execute permission to the owner of the file.
g+x adds execute permission to the group owner of the file.
o+x adds execute permission to other users.
making chmod u+x g+x o+x hello that adds execution permission to the owner, the group owner and the other users, to the file hello.

8-James_Bond
0 for the owner (no permissions).
0 for the group (no permissions).
7 for other users (read, write, and execute permissions).
making chmod 007 hello.

9-John_Doe
7 (rwx) for the owner (read, write, execute).
5 (r-x) for the group (read, execute).
1 (wx) for other users (write, execute).
making chmod 751 hello

10-mirror_permissions
chmod --reference=olleh hello sets the permissions of the file hello to be the same as the permissions of the file olleh.

11-directories_permissions
find . -type d: Searches for all directories starting from the current directory.
-exec chmod 755 {} \;: For each directory found, it adds execute permissions for the owner, the group owner, and other users using chmod 755.


