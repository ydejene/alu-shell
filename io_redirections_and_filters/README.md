Shell Scripting Basics
This directory contains a collection of fundamental shell scripts demonstrating basic Linux commands and scripting concepts. These scripts were created as part of an exercise to familiarize with common command-line operations and script execution.

Scripts Overview
Here's a brief description of each script included in this directory:

0-hello_world: A simple script that prints the classic "Hello, World" message to the standard output, followed by a new line.
1-confused_smiley: Displays a unique confused smiley face (Ôo)' to the standard output.
2-hellofile: Prints the entire content of the /etc/passwd file, which contains user account information on a Linux system.
3-twofiles: Displays the combined content of two important system files: /etc/passwd and /etc/hosts.
4-lastlines: Shows only the last 10 lines of the /etc/passwd file, demonstrating the use of the tail command.
How to Use
To run any of these scripts, you first need to ensure they have execute permissions.

Navigate to the directory:
Bash

cd /tmp/h
Grant execute permissions (if not already set): For a single script:
Bash

chmod u+x 0-hello_world
Or for all scripts in this directory:
Bash

chmod u+x *.sh  # If you name them with .sh extension
# OR if they don't have .sh extension and are named like 0-hello_world, 1-confused_smiley etc.
chmod u+x [0-9]-*
Execute the script:
Bash

./0-hello_world
./1-confused_smiley
# etc.
Author
Yonas Getachew Dejene
ALU BSE Student, January 2025 Intake

