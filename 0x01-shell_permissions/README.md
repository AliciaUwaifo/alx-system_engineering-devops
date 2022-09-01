su - switch current user to other user
whoami - prints the effective username of the current user
groups - print all the groups the current user is part of
chown - change the owner of a file
touch - to create an empty file
chmod - add permission to the owner of the file
chmod 754 - execute permission to the owner and the group owner, and read permission to the other users
chmod ugo+x - adds execution permission to the owner, the group owner and the other users
chmod 007 - gives owner and group no permission, but gives all permissions to other users
chmod 753 - gives owner all permissions, group read and execute permission, gives other users write and execute permissions
chmod --reference - sets the mode of the file
chmod -R a+X ./ - executes permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files remain unchanged
mkdir -m 751 my_dir - create a directory called my_dir with permissions 751 in the working directory
chgrp school hello - changes the group owner to school for the file hello
in the working directory
chown -R - changes the owner and the group owner for all the files and directories in the working directory
chown -h vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively
chown --from=guillaume betty hello - changes the owner of the file hello to betty only if its owned by the user guillaume
telnet towel.blinkenlights.nl - a script that will play the StarWars IV episode in the terminal
