#  proj1
C++ (bison, re-flex) version of project 1, scanner (aka lexer)

## To build 
(on a Unix system, including MacOS): 

`make`

This will invoke the Makefile in the 'src' directory
and produce a binary in the 'bin' directory. 
(Create a 'bin' directory on same level as 'src' if problems with make.)

## To run
(after building)

`bin/lexer samples/[whatever].qk` 

## To build and run Docker image:
`make image`
This will build a Docker image with src code.

`docker run -it proj1`
This will start a Docker container based on the image, lexer binary will already be made.
From interactive session, to run lexer:

`bin/lexer samples/[whatever].qk` 
