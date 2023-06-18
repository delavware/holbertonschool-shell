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
