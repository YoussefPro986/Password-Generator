# Password-Generator
Here, we will implement a menu drive program in C++ & C to generate random password with various combinations of alphabets and special

![2022-08-17_181437](https://user-images.githubusercontent.com/72635460/185190599-2f3b2b43-ef98-4e45-985b-ee82ed4482aa.png)

# C++ Random Password Generator
This is my version of a random password generator in C++. It's written to be used in the Windows terminal. It outputs 10 random passwords based off of the requirements specified. There are 2 requirements:

* Password length (between 1 and 50)
* Character sets (lowercase, uppercase, digits, and symbols)

You may specify password length from inside the program or on the command line. The character sets must be specified in the program. 

![2022-08-18_183027](https://user-images.githubusercontent.com/72635460/185447237-5c16851b-0bcf-4997-bcfa-5e91774c66e5.png)

To compile the program with the makefile, enter this command into the terminal:

`make`

To run the program, enter this command into the terminal (after compiling):

`./pwdgen`

OR

`./pwdgen [password length]`

To remove the binary file after being compiled and run, use this command:

`make clean`

## Character Sets
When specifying the character sets, there are 5 options - LC/lc (lowercase), UC/uc (uppercase), DG/dg (digits), SM/sm (symbols), and AL/al (all). Any invalid input results in the program ending. 

Example:
`lc UC dg` - that will give you a password with the lowercase, uppercase, and digit character sets. 
