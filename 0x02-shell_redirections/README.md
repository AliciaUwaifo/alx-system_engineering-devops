echo - writing a text in a text editor
echo "\"(Ôo)'" - displays a confused_smiley
cat /etc/passwd - displays the content of /etc/passwd file
cat /etc/passwd /etc/hosts - display the contents of /etc/passwd and /etc/hosts
tail /etc/passwd - displays the last 10 lines of /etc/passwd
head /etc/passwd - displays the first 10 lines of /etc/passwd
head -3 iacta | tail -1 - displays the third line of the file iacta
echo -e - script that creates a file named  \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
ls -la >> ls_cwd_content - script that writes into the file ls_cwd_content the result of the comman ls -la
tail -1 iacta >> iacta - a script that the duplicates the last line of the file iacta
find . -type f -name '*.js' -delete - a script that deletes all the regular files (not the directories) with a .js extension that are preesent in the current directory and all its subfolders
find -mindepth 1 -type d | wc -l - a script that counts the number of directories and sub-directories in the current directory
ls -t . | head - a script that displays the 10 newest files in the current directory
sort | uniq -u - a script that takes a list of words as input and prints only words that appear exactly once
egrep 'root' /etc/passwd - displays lines containing pattern "root" from the file /etc/passwd
egrep -c 'bin' /etc/passwd - diplays the number of lines that contain the pattern "bin" in the file /etc/passwd
egrep -A 3 'root' /etc/passwd - displays the lines containing the pattern "root" and 3 lines after them in the file /etc/passwd
egrep -v 'bin' /etc/passwd - displays all the lines in the file /etc/passwd that do not contain the pattern "bin"
egrep ^[[:alpha:]] /etc/ssh/sshd_config - displays all the lines of  the file /etc/ssh/sshd_config starting with a letter
tr 'Ac' 'Ze' - to replace all characters A and c from input to Z ande respectively
tr -d Cc - a script that removes all lettters c and C from input
rev - a script that reverse its input
cut -f 1,6 -d ':' /etc/passwd | sort - a script that displays all users and their home directories, sorted by users
find . -empty -printf "%f\n" - finds all empty files and directories in the current directory and all the sub-directories
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f  - a script that lists all the files with a .gif extension in the current directory and all its sub-directories
echo "$(cut -c 1 | tr -d '\n')" - a script that decodes acrostics that use the first letter of each line
tail -n +2 | cut -f 1 | sort | uniq -c | sort -nr | head -11 | cut -c 9-  - a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests
