# CSE 307 Assignment :four:

## Student Information :mortar_board:
- Name: Bryan Lai
- ID: 113789803 
- Professor: Yanhong (Annie) Liu

## Python :snake:: a4main.py
This file was written using Python 3.9 and uses TPG and sys.
It reads a file with expressions separated by new lines and follows the guidelines in the assignment listed down below.

To run this file, type ```py a4main.py <.txt file with correct format>```
One example of running this with one of the test .txt files is ```py a4main.py testfiles/a4input1.txt```
Doing this will lead to the desired output being printed in stdout.

## Project Implementation (AST!) 
Your interpreter program should take a single argument, which is an input file containing a MustScript program.

Your interpreter program should try to parse the input program, execute the program, and print the following outputs:


:one: If the input program contains a syntax error, your interpreter program should print Parsing Error.

:two: Otherwise, if one of the "must" conditions specified above is violated when executing the program, your interpreter program should print out Evaluation Error.

:three: Otherwise, your interpreter program should execute as specified.

## Sources Used/Afterword :book:
To complete this assignment, I checked the Official Python Library for help on specific syntax and reviewed the submissions in Google Classroom surrounding one of the Node's exec() methods. 