(0-alias) alias ls='rm *' - creates a script that creates an alias
(1-hello_you) echo hello $USER -  a script that prints hello user, where user is the current Linux user
(2-path) export PATH=$PATH:/action
(3-paths) echo $(printf $PATH | tr ":" "\n" | wc -w) - creates a script that counts the number of directories in the PATH 
(4_global_variables) printenv - a script that lists environment variables
(5-local_variables) set | less - a script that lists all local variables and environment variables, and functions
(6-create_local_variable) BEST="School" - a script that create a new local variable
(7-create_global_variable) export BEST="School" - a script that creates a new global variable
(8-true_knowledge) echo $((128 + TRUEKNOWLEDGE)) - a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
(9-divide_and_rule) echo $((POWER / DIVIDE)) - a script that prints the result of POWER divided by DIVIDE, followed by a new line
(10-love_exponent_breath) echo $((BREATH**LOVE)) - a script that displays the result BREATH to the power LOVE
(11-binary_to_decimal) echo $((2#$BINARY)) - a script that converts a number from base 2 to base 10
(12-combinations) echo {a..z}{a..z} | tr " " "\n" | egrep -v "oo" - create a script that prints all possible combinations of two letters, except oo
(12-print_float) printf "%.2f\n" $NUM - a script that prints a number with teo decimal places, followed by a new line
(100-decimal_to_hexadecimal) printf '%x\n' $DECIMAL - a script that converts a number from base 10 to base 16
(101-rot13) tr '[A-Za-z]' '[N-ZA-Mn-za-m]' - a script that encodes and decodes text using the rot13 encryption. Assume ASCII
(102-odd) cat -n | cut -c6- | grep -vP "[02468]\t" | cut -f2 - a script that prints every other line from the input, starting with the first line
(103-water_and_stir) - a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result
