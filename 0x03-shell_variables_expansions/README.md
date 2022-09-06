(0-alias) alias ls='rm *' - creates a script that creates an alias
(1-hello_you) echo hello $USER -  a script that prints hello user, where user is the current Linux user
(2-path)
(3-paths) echo $(printf $PATH | tr ":" "\n" | wc -w) - creates a script that counts the number of directories in the PATH 
(4_global_variables) printenv - a script that lists environment variables
(5-local_variables) set | less - a script that lists all local variables and environment variables, and functions
(6-create_local_variable) BEST="School" - a script that create a new local variable
(7-create_global_variable) export BEST="School" - a script that creates a new global variable
(8-true_knowledge) echo $((128 + TRUEKNOWLEDGE)) - a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
(9-divide_and_rule) echo $((POWER / DIVIDE)) - a script that prints the result of POWER divided by DIVIDE, followed by a new line
