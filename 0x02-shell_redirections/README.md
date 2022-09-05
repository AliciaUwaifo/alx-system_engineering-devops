echo - writing a text in a text editor
echo "\"(Ôo)'" - displays a confused_smiley
cat /etc/passwd - displays the content of /etc/passwd file
cat /etc/passwd /etc/hosts - display the contents of /etc/passwd and /etc/hosts
tail /etc/passwd - displays the last 10 lines of /etc/passwd
head /etc/passwd - displays the first 10 lines of /etc/passwd
head -3 iacta | tail -1 - displays the third line of the file iacta
echo -e - script that creates a file named  \*\\'"Best School"\'\\*$\?\*\*\*\*\*\*:) containing the text Best School ending by a new line
ls -la >> ls_cwd_content - script that writes into the file ls_cwd_content the result of the comman ls -la
tail -1 iacta >> iacta - a script that the duplicates the last line of the file iacta
find . -type f -name '*.js' -delete - a script that deletes all the regular files (not the directories) with a .js extension that are preesent in the current directory and all its subfolders
find -mindepth 1 -type d | wc -l - a script that counts the number of directories and sub-directories in the current directory
ls -t . | head - a script that displays the 10 newest files in the current directory
sort | uniq -u - a script that takes a list of words as input and prints only words that appear exactly once
egrep 'root' /etc/passwd - displays lines containing pattern "root" from the file /etc/passwd 
