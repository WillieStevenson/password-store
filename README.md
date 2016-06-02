# password-store
A simple terminal-based password manager written in Bash and managed by sqlite.

This is a small, light-weight, terminal-based password manager app I wrote because I was tired of hearing about online-based password manging sites being breached. I was also tired of keeping my passwords stored in an unorganized text file.


## Installation

1. Clone the repository.
2. Preferably store both files in a place accessible from one of the paths in PATH so that the script is accessible from anywhere.
3. Make the script executable.
4. Run `password-store -C` to initiate the password store database creation process. (Upon creation, the database and config will be stored in ~/.pw/)
5. Use `-h` to read the program's usage.


## Important!

+ This is a simple/naive password manager. It does not employ encryption (using gpg or other means). It does however protect the directory and the database file with the file system so that it is only `rw` to the user creating it. For this reason, I recommend you only run this application on a computer where you are the sole owner or have root permissions. 


## To Do

+ Probably something I am forgetting.