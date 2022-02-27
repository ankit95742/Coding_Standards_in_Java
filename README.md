# Coding_Standards_in_Java

## Why Coding Standards?

The coding standards are important because most of the software cost goes toward maintenace. And also, the software is not always developed by a single developer. Therefore, maintaing a convention for writing software increases the readability of the program.

## Basic Coding Rules to Follow

1. Use descriptive and appropriate names for all identifiers (variables, method names, class names, constants, etc.)
2. Comment every 3-7 lines of code.
3. Be Neat.

## 1. Naminng Conventions

1. Package names are typed in lowercase e.g. javax.sql, com.newpackage, java.lang. Some not preferable ones are e.g. com.newPackage, com.new_package.

2. Class, enum, interface, and annotation names are typed in UpperCamelCase e.g. Thread, Runnable, Person.

3. Constants are types in uppercase separated by an underscore e.g. SIZE, MIN_VALUE,MAX_VALUE.
 
4. Methods names are verbs and are typed in a lowerCamelCase e.g. deleteCharAt(), add(), isNull().

5. Variables are typed in lowerCamelCase e.g. employeeName, birthDate, email. The name should be short and such that it tells the reader of the program what this variable stores.

## 2. Curly Braces

Curly braces are used to define the bodies of classes, method and loops. There are two standard formats for the usage of curly braces, either of which is used.

1. No black lines should be present after the opening brace or before the closing brace.

2. A curly brace is applied at the end of the line that starts the class, method, loop, etc., and the closing brace is on a line by itself, lined up vertically with the start of the first line.

## 3. Comments

Comments are an integral part of any program. They help the person reading the code (often you) better understand the intent and functionality of the program. It is critical that you get in the habit of always commenting your code and doing it as you write your code, not after the fact.

There are two types of comments that should appear in programs: documentation comments and implementation comments. Documentation comments describe the semantics of a class, field, or method. documentation comments are an integral part of programming and are mandatory in this class.

By convention, in Java, documentation comments are set inside the comment delimiters /** ... */ with one comment per class, interface, or member. The comment should appear right before the declaration of the class, interface or member and each line of the comment should begin with a "*".

## 4. White Space

1. Operators should be surrounded by a space character. For example:
 
2. Reserved words of Java should be followed by white space. For example:

3. Commas should be followed by white space. For example:

4. Colons should be surrounded by white space. For example:

5. Semicolons in for statements should be followed by a space character. For example:

## 5. Declarations:

1. One declaration per line is recommended since it encourages commenting and enhances the clarity of code.

2. The static/class variables should be placed in the sequence: First public class variables, protected, package/default level i.e. with no access modifier and then the private.

3. Next, class constructors should be declared followed by the inner classes, if applicable.

4. Local declarations that hide declarations at higher levels should be avoided. For example, the same variable name in an inner block as of the global variable should be avoided.

5. Declarations for local variables should be only at the beginning of blocks.

6. Numerical constants should not be coded directly.














