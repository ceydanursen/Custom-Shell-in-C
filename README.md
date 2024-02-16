# Custom-Shell-in-C
## __Abstract:__

The project I developed is a custom shell in C. This custom shell provides users a CLI to

interact with OS. The aim of this project is to develop a shell which can handle following

operations: command executing, redirecting output, handling aliases and implementing bello

command.


### __Explanation of the general methods used:__

The algorithm's core strategy involves several steps. Initially, it tokenizes user input, seeking

the specified command within the PATH variable, and upon discovery, executes it. The shell

manages specific scenarios like alias definitions, bello commands, redirection operations,

and background processing.

#### __1) The tools used:__
  
Primarily, the project makes extensive use of system calls, file handling mechanisms,

and process management techniques.

#### __2) Approach:__

+ Implementing functions for parsing
  
- Used fork-exec mechanism for all execution
  
+ Creation of dedicated functions for output redirection, alias handling, and bello
  
command execution

- Error handling
  
+ Checking PATH before every execution


## __Installation__

Before running the below commands, make sure you have  

+ GCC compiler  

- Linux OS (prefereably Ubuntu)

Run the following commands to start the shell.

    $ make
  
    $ ./shell
