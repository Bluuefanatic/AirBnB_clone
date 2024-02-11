# AirBnB Clone Project

This is the first step towards building an AirBnB clone. The project involves creating a command interpreter to manage AirBnB objects, implementing a parent class for object initialization, serialization, and deserialization, creating various classes for AirBnB entities, and developing a file storage engine.

## Command Interpreter

The command interpreter allows you to manage AirBnB objects through a shell-like interface. You can create new objects, retrieve objects, perform operations on objects, update attributes, and destroy objects.

### How to Start

To start the command interpreter, run the `console.py` script:

```bash
$ ./console.py

How to Use
Once the shell is running, you can enter commands. Some example commands include:

Creating a new User:
(hbnb) create User

Retrieving objects:
(hbnb) show User 123

Updating attributes:
(hbnb) update User 123 name "John Doe"

Destroying objects:
(hbnb) destroy User 123

Exiting the shell:
(hbnb) quit

Examples

Interactive Mode:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

Non-Interactive Mode:
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
