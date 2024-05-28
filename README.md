# AirBnB Clone - The Console

This AirBnB console is like creating a minishell that works in an interactive mode as well as non-interactive mode

## How to start it

To start the console we use the command: ./console.py

## How to use it 

We use the cmd interprete to create, update, destroy, quit object s basically showing all commands 
We can store an object to a file name (JSON file)

### Example of an interactive mode
 ```

 $ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
### Example of a non-interactive mode

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
    ```
* All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash    
