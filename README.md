# system_engineering-devops
This repository contains a linux bash script the prints the current working directory
## Script
The script starts with the shebang #!/bin/bash  which tells the command pwd to use the bash command in execution
However, before the the file 0-current_working_directory will execute, the owner must be given read and write permissions using the chmod command
The user permission is givens as follows chmod u+x 0-current_working_directory, then the file is now good to execute
The script then executes with the command ./0-current_working_directory. This is because, the sheban command was used to begin the file


