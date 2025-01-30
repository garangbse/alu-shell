# 0. Where am I?
It shows the complete path from the root directory to the folder where the script is run. It uses the pwd command to get and display this information.

# 1. What’s in there?
The script runs the pwd (print working directory) command which retrieves and prints the full path of the directory where the script is being executed.

# 2. There is no place like home
The script runs cd ~, which changes the working directory to the home directory of the user running the script.

# 3. The long format
The ls lists the files and directories in the current directory and the -l option (long format) provides detailed information about each file

# 4. Hidden files
The ls lists the files and directories in the current directory, the -l option (long format) provides detailed information about each file and the ls lists the files and directories in the current directory and the -l option (long format) provides detailed information about each file.

# 5. I love numbers
The ls lists the files and directories in the current directory, the -l option (long format) provides detailed information about each file and the ls lists the files and directories in the current directory, the -l option (long format) provides detailed information about each file and the -n option displays user and group IDs as numbers instead of names.

# 6. Welcome
mkdir is used to make the "myfirstdirectory" directory.
/tmp/myfirstdirectory specifies the location where the new directory will be created.

# 7. Betty in my first directory
mv is used to move or rename files.

# 8. Bye bye Betty
rm (remove) is used to delete files.

# 9. Bye bye My first directory
rmdir (remove directory) is used to delete empty directories.

# 10. Back to the future
cd is used to change the working directory, the "-" argument with cd takes you to the previous directory. It works by switching back to the last directory the user was in before the current one.

# 11. Lists
ls -la . lists files in the current directory.
ls -la .. lists files in the parent directory.
ls -la /boot lists files in the /boot directory.

# 12. File type
file is used to determine the type of a file.
Running file /tmp/iamafile will output information about the file's type

# 13. We are symbols, and inhabit symbols
ln is the command used to create links.
The -s option creates a symbolic (soft) link instead of a hard link.
making ln -s /bin/ls __ls__ that creates a symbolic link to /bin/ls, named __ls__

# 14. Copy HTML files
cp → The command to copy files.
-u → (update) Only copies files if they are newer or don’t exist in the destination.
*.html → Selects all files with the .html extension in the current directory.
.. → Specifies the parent directory as the destination.
making cp -u *.html .. that copies all .html files from the current working directory to its parent directory

# 15. Let’s move
mv → Moves files.
[A-Z]* → Matches all files starting with an uppercase letter (A-Z).
making mv [A-Z]* /tmp/u

# 16. Clean Emacs
rm → Command to remove (delete) files.
-f → Forces deletion without asking for confirmation, even if the file is write-protected.
*~ → Matches all files ending with ~ in the current directory.
making rm -f *~ that deletes all files in the current working directory that end with the ~ character 

# 17. Tree
mkdir → Creates directories.
-p → Ensures that all parent directories (welcome/ and welcome/to/) are created if they don’t already exist.
welcome/to/school → Specifies the full directory path to be created.
making mkdir -p welcome/to/school

