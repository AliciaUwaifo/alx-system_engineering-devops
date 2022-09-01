su - switch current user to other user
whoami - prints the effective username of the current user
groups - print all the groups the current user is part of
chown - change the owner of a file
touch - to create an empty file
chmod - add permission to the owner of the file
chmod u+x, g+x, o+r - execute permission to the owner and the group owner, and read permission to the other users
chmod ugo+x - adds execution permission to the owner, the group owner and the other users
chmod 007 - gives owner and group no permission, but gives all permissions to other users
chmod 753 - gives owner all permissions, group read and execute permission, gives other users write and execute permissions
chmod --reference - sets the mode of the file
chmod -R a+X ./ - executes permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files remain unchanged
mkdir -m 751 my_dir - create a directory called my_dir with permissions 751 in the working directory
