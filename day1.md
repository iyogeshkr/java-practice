# Java:
- Object oriented Programming Language
- released 1995 by James Gosling at sun microsystems
- later oracle brought it

# Features:
-Platform independent
- WORA - write once run anywhere
- Collection API
- Multithreading
- Exception handling

# Shortcuts:
1. IDE - Integrated Development Environment
2. Compiler - JavaC
3. JDK - Java Development Kit
4. Jshell - simpler program execution in shell, introduced in java 9
5. JVM - Java Virtual Machine
6. LTS - Long Term Support

# Steps:
JAVA CODE (.java) --Compiler (javaC) -- Bytecode (.class) -- JVM (understand bytecode)

- java code can run on any os (not all os), need to have JVM installed on it
- JVM doesnt accept code directly, it understand bytecode.
- Java code is platform independent but JVM is PF dependent.
- only JRE & JVM required to run a java program

# Hierarchy
JVM - contain lib
JRE - Java Runtime Environment
OS
Hardware

[JDK [JRE [JVM]]] - show which is subpart of which

# Data, S/W & Variable:
1. Data - to process - from users - store - db [permanent/Persistent]
For Processing - temporary store - variable

2. Java - strong typed lang - enforce data rules at both compile time and runtime

3. Software - virtual simulation of real world - built - to solve real world problems

4. print() - to print, println() - print in next line


# Data Types:
1. Primitive: integer, float

- integer:
    byte - 1 byte 
    short - 2 byte
    int - 4 byte - (-2^31 to 2^31-1)
    long  -8 byte [need to mention l, long l = 1000l]

- float:
    double (by default) - 8 byte
    float - 4 byte [need to mention explicitly; float num - 5.6f]

- char - 2 byte. Unicode, not in ASCII(like c); char c = 'k';

- boolean - true or false. Not 0/1 like c. boolean b = true;

# some important points:
- a number can also be a char; {a+1 = b}
- can use underscore between/below numbers for ease, no issue. eg: int num = 10_00_00_000;
- can use binary/hex style too. eg: int num = 0X7E; int num = 0b101
- they are also known as string literals. String literals is a sequence of char harcoded directly into the code.

# Type conversion & type casting
- every var needs: 1. name 2. type
- small value can be put in big var but reverse not done. eg: 
byte b = 127;
int a = 12;
b = a; Wrong -- b = (byte)a; - this os casting(Exlicit conversion)
a = b; right

