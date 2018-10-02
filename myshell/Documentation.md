Project Name: myshell (Simple Shell)
Yusuf Taylan YUKSEL : ytaylanyuksel@gmail.com
Emre ULAS           : emreulas25@gmail.com


LSH is a simple implementation of a shell in C.  It demonstrates the basics of how a shell works.
That is: read, parse, fork, exec, and wait.  Since its purpose is demonstration
(not feature completeness or even fitness for casual use), it has many
limitations, including:

* Commands must be on a single line.
* Arguments must be separated by whitespace.
* No quoting arguments or escaping whitespace.
* No piping or redirection.
* Only builtins are: `cd`, `help`, `exit`.
