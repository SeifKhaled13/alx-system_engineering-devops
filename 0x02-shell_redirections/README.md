<h1>Script 1</h1> - "Hello, World"
This script simply outputs the string "Hello, World" to the console. It is a basic introduction to shell scripting and serves as a starting point for learning more complex bash commands.

Script 2 - "(Ôo)'"
This script outputs the string ""(Ôo)'", which consists of a pair of double-quotes enclosing a pair of parentheses and the characters "\Ô" and "o". The backslash character is used to escape the single quote, which allows it to be included in the string. The overall result is a visually appealing representation of an owl.

Script 3 - "cat /etc/passwd"
This script prints the contents of the "/etc/passwd" file to the console. This file contains information about user accounts on the system.

Script 4 - "cat /etc/passwd /etc/hosts"
This script prints the contents of both the "/etc/passwd" and "/etc/hosts" files to the console.

Script 5 - "tail -n 10 /etc/passwd"
This script prints the last 10 lines of the "/etc/passwd" file to the console.

Script 6 - "head -n 10 /etc/passwd"
This script prints the first 10 lines of the "/etc/passwd" file to the console.

Script 7 - "head -n 3 iacta | tail -n 1"
This script prints the third line of the "iacta" file to the console.

Script 8 - "echo "Best School" > \*\\"'"Best School"\'"\\*$\?\*\*\*\*\*:)"
This script creates a file called "*\"'"Best School"\'"\*$?*****:)" in the current directory and writes the string "Best School" to it.

Script 9 - "ls -la > ls_cwd_content"
This script lists the contents of the current directory, including hidden files, and saves the output to a file called "ls_cwd_content".

Script 10 - "tail -n 1 iacta >> iacta"
This script appends the last line of the "iacta" file to the end of the same file.

Script 11 - "find . -type f -name "*.js" -delete"
This script deletes all files with the ".js" extension in the current directory and its subdirectories.

Script 12 - "find . -type d -not -name . | wc -l"
This script counts the number of directories in the current directory and its subdirectories.

Script 13 - "ls -t | head -n 10"
This script lists the contents of the current directory in reverse chronological order and prints the first 10 items.

Script 14 - "sort | uniq -u"
This script sorts the input it receives and prints only the unique lines.

Script 15 - "grep -i "root" /etc/passwd"
This script searches for the string "root" in the "/etc/passwd" file and prints all lines containing that string. The "-i" option makes the search case-insensitive.

Script 16 - "grep -c -i "bin" /etc/passwd"
This script counts the number of lines in the "/etc/passwd" file that contain the string "bin". The "-c" option makes grep output only the count.

Script 17
This script uses the grep command with the -i option to match the word "root" (case-insensitive) in the /etc/passwd file, and -A 3 option to print the 3 lines after the match.

Script 18
This script uses the grep command with the -i option to match any line that does not contain the word "bin" in the /etc/passwd file.

Script 19
This script uses the grep command with the -i option to match any line that starts with a lowercase letter in the /etc/ssh/sshd_config file.

Script 20
This script uses the tr command to replace all occurrences of "A" with "Z" and "c" with "e" in the input.

Script 21
This script uses the tr command to delete all occurrences of the letter "c" (both uppercase and lowercase) from the input.

Script 22
This script uses the rev command to reverse the order of characters in each line of the input.

Script 23
This script uses the cut command with the -d option to specify the delimiter as ":" and -f option to extract the first and sixth fields from each line of the /etc/passwd file. The output is then sorted in ascending order.

Script 24
This script uses the find command to search for empty files/directories in the current directory (.) and print their filenames in reverse order.

Script 25
This script uses the find command with the -type option to specify that only files should be searched, and the -name option to search for files with a ".gif" extension. The rev and cut commands are then used to extract the filename without the extension, and the output is sorted in a case-insensitive manner using LC_ALL=C sort -f.

Script 26
This script uses the cut command to extract the first character of each line of the input, and paste command to concatenate them into a single line.

Script 27
This script uses the tail, cut, sort, uniq, and head commands to extract the second column of data from a file, sort the data by the first column, count the unique values of the first column, sort the output in descending order of count, print the top 11 results, and then extract the second column again. Finally, rev and cut commands are used to print only the last word of each line in reverse order.
