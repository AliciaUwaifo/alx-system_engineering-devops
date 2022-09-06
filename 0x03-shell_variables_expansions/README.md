(0-alias) alias ls='rm *' - creates a script that creates an alias
(1-hello_you) echo hello $USER -  a script that prints hello user, where user is the current Linux user
(2-path)
(3-paths) echo $(printf $PATH | tr ":" "\n" | wc -w) - creates a script that counts the number of directories in the PATH 
(4 Global variables) printenv - a script that lists environment variables
(5 Local variables) set | less - a script that lists all local variables and environment variables, and functions
(6 Local variable) BEST="School" - a script that create a new local variable
