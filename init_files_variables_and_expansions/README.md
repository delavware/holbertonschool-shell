README.md for init_files
# TASKS
# 01. Create a script that prints hello user, where user is the current Linux user.
## RES: echo "hello $(whoami)"

# 09. Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
# POWER and DIVIDE are environment variables
## RES: printf "%d\n" $((POWER / DIVIDE))

# 10. Write a script that displays the result of BREATH to the power LOVE
# BREATH and LOVE are environment variables
# The script should display the result, followed by a new line
## RES: printf "%d\n" $(($BREATH**$LOVE))

# 11. Write a script that converts a number from base 2 to base 10.
# The number in base 2 is stored in the environment variable BINARY
# The script should display the number in base 10, followed by a new line
## RES: printf "%d\n" $((BINARY#0)) 
