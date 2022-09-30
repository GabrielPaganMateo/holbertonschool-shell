# Holberton School Shell Init files Variables and Expansions

## This directory was made to store the tasks and work done as part of the "Shell, init files, variables and expansions"

### Includes scripts with init files, variables and expansions commands within the shell

#### Script Descriptions:

0. alias ls="rm *" {Script that creates an alias
1. echo hello $USER {Prints hello user where user is the current Linux user
2. PATH=$PATH:/action {Add /action to the PATH
3. echo $PATH | tr : "\n" | wc -l {Counts the number of directories in the PATH
4. printenv {Lists environmental variables
5. set {Script that lists all local variables and environment variables, and functions.
6. BEST=School {Script that creates a new local variable
7. export BEST=School {Create a new global variable
8. echo $((128+$TRUEKNOWLEDGE)) {Prints the result of the addition of 128 with value stored in variable
9. echo $(($POWER/$DIVIDE)) {Script that prints the result of POWER divided by DIVIDE followed by a new line
10. echo $((BREATH*\*LOVE)) {Script that displays the result of BREATH to the power LOVE
11. echo $((2#$BINARY)) {Converts a number from base 2 to base 10
12. echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo {Script that prints all possible combinations of two letters
13. printf "%.2f\n" $NUM {Print a number with two decimal places
14. printf "%x\n" $DECIMAL {Script that converts a number from base 10 to base 16
15. tr 'a-zA-Z' 'n-za-mN-ZA-N' {encodes and decodes text using the rot13 encryption
16. perl -ne 'print if (++$x)%2' {script that prints every other line from the input, starting with the first line
17. echo $(printf %o $(($((5#$(echo $WATER | tr 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol') {adds the two numbers stored in the environment variables WATER and STIR and prints the result


