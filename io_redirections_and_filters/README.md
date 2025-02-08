# 0-hello_world
- `#!/bin/bash` - This line specifies the script should be run using the Bash shell.
- `echo` - is used to print the string "Hello, World" to the terminal.

# 1-confused_smiley
- `echo` - is used to print the string "(Ôo)'".

# 2-hellofile
- `cat` - is used to display the content of the file `hello`.

# 3-twofiles
- `cat` - is used to display the content of the files `hello` and `world`.

# 4-lastlines
- `tail` - is used to display the last 10 lines of the file `hello`.

# 5-firstlines
- `head` - is used to display the first 10 lines of the file `hello`.

# 6-third_line
- `head -n 3` - is used to display the first 3 lines of the file `hello`.
- `tail -n 1` - is used to display the last line of the output from the `head` command, effectively showing the third line of the file `hello`.

# 7-file
- `echo` - is used to print the string "Best School" and redirect it to the file `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:`.
- `>` - is used to redirect the output of the `echo` command to the file, creating the file if it doesn't exist or overwriting it if it does.

# 8-cwd_state
- `ls -la` - is used to list all files and directories in the current directory in long format, including hidden files.
- `>` - is used to redirect the output of the `ls -la` command to the file `ls_cwd_content`.

# 9-duplicate_last_line
- `tail -n 1` - is used to display the last line of the file `iacta`.
- `>>` - is used to append the output of the `tail -n 1` command to the file `iacta`.

# 10-no_more_js
- `find . -type f -name "*.js"` - is used to find all files with the `.js` extension in the current directory and its subdirectories.
- `-delete` - is used to delete the files found by the `find` command.

# 11-directories
- `find . -type d` - is used to find all directories in the current directory and its subdirectories.

# 12-newest_files
- `ls -lt` - is used to list all files and directories in the current directory, sorted by modification time in descending order.
- `head -n 10` - is used to display the first 10 lines of the output from the `ls -lt` command, effectively showing the 10 newest files.

# 13-unique
- `sort` - is used to sort the lines of the file `list`.
- `uniq` - is used to remove duplicate lines from the sorted output.

# 14-findthatword
- `grep` - is used to search for the string "root" in the file `/etc/passwd`.

# 15-countthatword
- `grep -c` - is used to count the number of lines containing the string "bin" in the file `/etc/passwd`.

# 16-whatsnext
- `grep -A 3` - is used to display the string "root" and the 3 lines following each match in the file `/etc/passwd`.

# 17-hidethisword
- `grep -v` - is used to display all lines in the file `/etc/passwd` that do not contain the string "bin".

# 18-letteronly
- `grep -i` - is used to search for lines containing the letters `a` and `c` in the file `/etc/ssh/sshd_config`, ignoring case.
- `tr -cd 'a-zA-Z'` - is used to delete all characters except letters from the output of the `grep` command.

# 19-AZ
- `tr 'A' 'Z'` - is used to replace all occurrences of the character `A` with the character `Z` in the input.
- `tr 'c' 'e'` - is used to replace all occurrences of the character `c` with the character `e` in the input.

# 20-hiago
- `tr -d 'cC'` - is used to delete all occurrences of the characters `c` and `C` from the input.

# 21-reverse
- `rev` - is used to reverse the characters in each line of the input.

# 22-users_and_homes
- `cut -d ':' -f 1,6` - is used to extract the first and sixth fields (username and home directory) from each line of the file `/etc/passwd`, using `:` as the field delimiter.
- `sort` - is used to sort the extracted fields.

# 23-empty_casks
- `find . -type f -empty` - is used to find all empty files in the current directory and its subdirectories.

# 24-gifs
- `find . -type f -name "*.gif"` - is used to find all files with the `.gif` extension in the current directory and its subdirectories.
- `-printf '%f\n'` - is used to print the names of the files found, without their directory paths.

# 25-acrostic
- `cut -c 1` - is used to extract the first character of each line from the file `acrostic`.
- `paste -s -d ''` - is used to join the extracted characters into a single line without any delimiters.

# 26-the_biggest_fan
- `tail -n +2` - is used to skip the first line of the file `input`.
- `sort -k 1,1` - is used to sort the remaining lines by the first field.
- `uniq -c` - is used to count the number of occurrences of each unique line.
- `sort -nr` - is used to sort the lines in descending order by the count.
- `head -n 1` - is used to display the line with the highest count.
