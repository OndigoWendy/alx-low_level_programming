# ALX Engineering
## Preprocessor
 1.Write a script that runs a C file through the preprocessor and save the result into another file.

The C file name will be saved in the variable $CFILE
The output should be saved in the file c

## How gcc works
The -E option causes gcc to run the preprocessor, display the expanded output, and then exit without compiling the resulting source code.
<table>
        <thead>
                <td>
                        <b>SUMMARY</b>
                </td>
                <td>
                        <b>SUMMARY</b>
                </td>
        </thead>
        <tr>
                <td>
                        <img width="289" alt="code-one" src="https://miro.medium.com/max/1400/1*eRUmU8AUTzVgHDJh5m50Qw.jpeg">
                </td>
                <td>
                        <img width="306" alt="render-one" src="https://www3.ntu.edu.sg/home/ehchua/programming/cpp/images/CompilationProcess.png">
                </td>
        </tr>
       
</table>

I was using the WSL so:
To run directly in a Linux console:

vim file.txt +"set ff=unix" +wq

## Compiler
2.Write a script that compiles a C file but does not link.

The C file name will be saved in the variable $CFILE

<table>
        <thead>
                <td>
                        <b>SUMMARY</b>
                </td>
                <td>
                        <b>SUMMARY</b>
                </td>
        </thead>
        <tr>
                <td>
                        <img width="381" alt="code-two" src="https://slidetodoc.com/presentation_image/1b46abb6cbee828587d12425094b5114/image-33.jpg">
                </td>
                <td>
                        <img width="307" alt="render-two" src="https://cs.brown.edu/courses/csci1310/2020/assign/labs/assets/lab2-compilation.png">
                </td>
        </tr>
       
</table>

## Assembler
  Write a script that generates the assembly code of a C code and save it in an output file.

* The C file name will be saved in the variable $CFILE
* The output file should be named the same as the C file, but with the extension .s instead of .c.
Example: if the C file is main.c, the output file should be main.s

## Name
Write a script that compiles a C file and creates an executable named cisfun.

* The C file name will be saved in the variable $CFILE

## Hello,puts
  Write a C program that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.

* Use the function puts
* You are not allowed to use printf
* Your program should end with the value 0

## Hello,printf
Write a C program that prints exactly with proper grammar, but the outcome is a piece of art,, followed by a new line.

* Use the function printf
* You are not allowed to use the function puts
* Your program should return 0
* Your program should compile without warning when using the -Wall gcc option

## Size is not grandeur, and territory does not make a nation
 Write a C program that prints the size of various types on the computer it is compiled and run on.

* You should produce the exact same output as in the example
* Warnings are allowed
* Your program should return 0
* You might have to install the package libc6-dev-i386 on your Linux to test the -m32 gcc option

## Intel
Write a script that generates the assembly code (Intel syntax) of a C code and save it in an output file.

* The C file name will be saved in the variable $CFILE.
* The output file should be named the same as the C file, but with the extension .s instead of .c.
* Example: if the C file is main.c, the output file should be main.s

##  UNIX is basically a simple operating system, but you have to be a genius to understand the simplicity

Write a C program that prints exactly and that piece of art is useful" - Dora Korpar, 2015-10-19, followed by a new line, to the standard error.

* You are not allowed to use any functions listed in the NAME section of the man (3) printf or man (3) puts
* Your program should return 1
* Your program should compile without any warnings when using the -Wall gcc option
