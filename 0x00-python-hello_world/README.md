Tasks

0. Run Python file

mandatory

Write a Shell script that runs a Python script.



The Python file name will be saved in the environment variable $PYFILE



guillaume@ubuntu:~/py/0x00$ cat main.py 

#!/usr/bin/python3

print("Best School")



guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py

guillaume@ubuntu:~/py/0x00$ ./0-run

Best School

guillaume@ubuntu:~/py/0x00$
1. Run inline

mandatory

Write a Shell script that runs Python code.



The Python code will be saved in the environment variable $PYCODE



guillaume@ubuntu:~/py/0x00$ export PYCODE='print(f"Best School: {88+10}")'

guillaume@ubuntu:~/py/0x00$ ./1-run_inline 

Best School: 98

guillaume@ubuntu:~/py/0x00$
2. Hello, print

mandatory

Write a Python script that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.



Use the function print

guillaume@ubuntu:~/py/0x00$ ./2-print.py 

"Programming is like building a multilingual puzzle

guillaume@ubuntu:~/py/0x00$
Complete this source code in order to print the integer stored in the variable number, followed by Battery street, followed by a new line.



You can find the source code here

The output of the script should be:

the number, followed by Battery street,

followed by a new line

You are not allowed to cast the variable number into a string

Your code must be 3 lines long

You have to use f-strings tips

guillaume@ubuntu:~/py/0x00$ ./3-print_number.py

98 Battery street

guillaume@ubuntu:~/py/0x00$
4. Print float

mandatory

Complete the source code in order to print the float stored in the variable number with a precision of 2 digits.



You can find the source code here

The output of the program should be:

Float:, followed by the float with only 2 digits

followed by a new line

You are not allowed to cast number to string

You have to use f-strings

guillaume@ubuntu:~/py/0x00$ ./4-print_float.py

Float: 3.14

guillaume@ubuntu:~/py/0x00$
5. Print string

mandatory

Complete this source code in order to print 3 times a string stored in the variable str, followed by its first 9 characters.



You can find the source code here

The output of the program should be:

3 times the value of str

followed by a new line

followed by the 9 first characters of str

followed by a new line

You are not allowed to use any loops or conditional statement

Your program should be maximum 5 lines long
6. Play with strings

mandatory

Complete this source code to print Welcome to Holberton School!



You can find the source code here

You are not allowed to use any loops or conditional statements.

You have to use the variables str1 and str2 in your new line of code

Your program should be exactly 5 lines long

guillaume@ubuntu:~/py/0x00$ ./6-concat.py

Welcome to Holberton School!

guillaume@ubuntu:~/py/0x00$ wc -l 6-concat.py

5 6-concat.py

guillaume@ubuntu:~/py/0x00$
7. Copy - Cut - Paste

mandatory

Complete this source code



You can find the source code here

You are not allowed to use any loops or conditional statements

Your program should be exactly 8 lines long

word_first_3 should contain the first 3 letters of the variable word

word_last_2 should contain the last 2 letters of the variable word

middle_word should contain the value of the variable word without the first and last letters
8. Create a new sentence

mandatory

Complete this source code to print object-oriented programming with Python, followed by a new line.



You can find the source code here

You are not allowed to use any loops or conditional statements

Your program should be exactly 5 lines long

You are not allowed to create new variables

You are not allowed to use string literals
9. Easter Egg

mandatory

Write a Python script that prints “The Zen of Python”, by TimPeters, followed by a new line.



Your script should be maximum 98 characters long (please check with wc -m 9-easter_egg.py)
10. Linked list cycle

mandatory

Technical interview preparation:



You are not allowed to google anything

Whiteboard first

This task and all future technical interview prep tasks will include checks for the efficiency of your solution, i.e. is your solution’s runtime fast enough, does your solution require extra memory usage / mallocs, etc.

Write a function in C that checks if a singly linked list has a cycle in it.



Prototype: int check_cycle(listint_t *list);

Return: 0 if there is no cycle, 1 if there is a cycle

Requirements:



Only these functions are allowed: write, printf, putchar, puts, malloc, free
