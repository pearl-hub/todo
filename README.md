TODO
====
Allows recursively to search for TODOs inside every files in the directories
specified by the user. It is also possible to add new generics TODOs in the
default file. Type *todo --help* to see all the available options.

Example of using:

    $ todo
    Lists the generics TODOs and the TODOs contained into every files in the
    directories specified by the user.

    $ todo 'This is a new TODO'
    Adds a new TODO into the default file.

    $ todo -r 'NUM'
    Removes the TODO specified by the user.

    $ todo -a '<new/path>'
    Adds a new path to look for TODOs.

    $ todo -l
    Lists the available paths.

    $ todo -d 'NUM'
    Removes the paths specified by the entry.
