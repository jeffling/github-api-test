Your task is to fetch the list of files and directories from our github repository here:

    https://github.com/10sheet/interview-repo

Each directory's content should be ordered by file size, but directories should come first.

You should display the content in a format like the below example:

    a/
        1.md
        2.txt
        3.mov
    b/
        c/
            4.asm
            5.c
            6.scala
        7.java
        8.py
        9.js

The application should take one argument, *depth of the output*.

For example, if the depth is 2 in the above example, the output will show:

    a/
        1.md
        2.txt
        3.mov
    b/
        c/
        7.java
        8.py
        9.js

This should be written in Scala, preferrably with tests that we can run. How you get the above information is up to you.
