JAVA Programs (and most other programming languages) have keywords.Each has as a specific meaning and sometimes they need to used in specific orders 

you write java programs by following a specific set of rules,using a combination of these keywords and other things you will see which collectively form and
java program 

Note:Keywords are case sensitive -public and public and even PUBLIC are different things.

PUBLIC AND CLASS are two JAVA Keywords--->They have a specific meaning.

The PUBLIC java keyword is an access modifier .An access modifier allow us to define the scope or how parts of your code or even some else's code
can access this code more on later

CLASS

-->Defining a class.The Class keyword is used to define a class with name following the keyword-(ie) Hello in this case and left and right curly braces to define
the class block

-->To define a class requires an optional access modifier,followed by class,followed by the left and right curly braces

-->The left and right curly braces are defining the class body--anything in between them is "PART" of this class.we can have data and code..


MAIN METHOD

Method-->It's a collection of statements (one or more) that performs an operation.we'll be using a special method called the main method that java looks for
when running a program.It's the entry point of JAVA CODE

VARIABLES:

Variables are a way to store information in our computer.variables that we define in a program can be accessed by a name we give them,and the computer does the
hard work of figuring out where they get stored in the computers random access memory(RAM)

There are lot of different types of data we can define for our variables.collectively these are known as datatypes.As you may have guessed,datatypes are 
keywords in JAVA

To define a variable we need to specify the datatype,then give our variable a name and optionally add an expression to initialize the variable with a value

EXPRESSION-->This is a construct that evaluates to a single value

STRING LITERAL

-->Any sequence of characters surrounded by double quotes in a string literal in java.it's value cannot be changed ,unlike a variable

Primitive Types:

Java primitive types are the most basic data types.The int is one of eight primitive types.

->char
->byte
->short
->int
->float
->double-->At last we use d
->long --->To declare long we put l on the last to tell the computer  that is the long value
->boolean

Wrapper Classes:

JAVA uses the concept of a wrapper class for all eight primitive types-In the case of an int we can use Integer and by doing that it gives us ways to 
perform operations on an int

Overflow and Underflow in JAVA

If you try to put a value larger than the maximum value in java or a value smaller than the minimum value in java,then you will get an overflow in the case
of the minimum value or an underflow in the case of the minimum

CASTING IN JAVA:

casting means to treat or convert a number from one type to another.we put the type we want to the number to be in parameter like this 

(byte)(minvalue/2);

Float(single precision) upto 7 decimal places and Double(double precision) upto 16 decimal places Primitive types:

unlike whole numbers,floating point numbers have fractional parts that we express with  a decimal point 3.14159 is an example.

Floating point numbers are also known as real numbers .we use floating point number when we need more precision in calculations.

precision refers to the format and amount of space occupied by the type.single precision occupies 32 bits and double occupies 64 bits.

Double if faster than float ie we use double in the program

double takes automatically a float when we don't define in the program

Boolean primitive type::

Boolean values allows for two choices true or false,yes or no ,1 or 0 in java terms we have a boolean primitive type and it can be set to two values only

STRING:: is not a primitive type it is a class

A string is a sequence of characters,a large number of characters

The string is a datatype in java,which is not a primitive type.it's actually a class 

Operators and operator Precedence

Operators in java are special symbols that perform specific operation on one,two,three operands and then return a result

Operand:: 

An operand is a term used to describe any object that is manipulated by an operator

example:int myvar = 15+12;  "+" is the operator and 15,12 are operands variables used instead of literals are also operands

EXPRESSION-->An expression is formed by combining variables,literals,method return values

if-then statement::

The if-then statement is the most basic of all the control flow statements.It tells your program to execute a certain section of code only if a
particular test evaluates to true

This is known as conditional logic

conditional logic uses specific statements in java to allow us to check a condition and execute certain code based on whether that condition (the expression)
is true or false

code block::A code block allows more than one statement to be executed

Logical AND and Logical OR operator-->&& ||

Ternary Operator-->The ternary operator is a shortcut to assigning one of two values to a variable depending on a given condition

EXPRESSION--> double kilometers = (100 * 1.699855) except double all are expressions datatype does not form expressions

STATEMENTS-->int myVariable = 50; it is the complete statement

super keyword-->the keyword super is used to access/call the parent class members(variables and methods)

this keyword-->the keyword this is used to call the current class members (variables and methods).This is required when we have a parameter with the same name
as an instance variable(field).


Method overloading:
Methods must have the same method name.
Methods must have different parameters

Method Overriding: 
Method overriding means defining a method in a child class that already exists in th parent class with same signature(same name,same arguments)
By extending the parent class the child class gets all the methods define in the parent class(those methods are also known as derived methods)

Method Overriding is also known as Runtime Polymorphism and Dynamic Method Dispatch,because the method that is going to be called is decided at run time
by the JVM.

When we override a method it's recommended to put @Override immediately above the method definition.This is an annotation that the compiler reads and will then
show us an error if we don' to follow overriding rules correctly.

We can't override static methods only instance methods can be override

constructors and private methods cannot be overriden.

Methods that are final cannot be overridden

STATIC METHODS::

static methods are declared using a static modifier

static methods can't access instance methods and instance variables directly

In static methods we can't use the this keyword.

Whenever you see a method that does not use instance variables that method should be created as a static method.

Instance Methods:

Instance methods belongs to an instance of a class

To use an instance method we have to instantiate the class first usually by using the new keywords.

Instance methods can access instance methods and instance variable directly

Instance methods can also static methods and static variables directly.


Instance Variables:

They don't use the static keyword

Instance Variables are also known as fields or member variables

Instance variables belongs to an instance of a class.

Every instance has it's own copy of an instance variable    

Every instance can have a different value(state)

Instance variable represents the state of an instance
