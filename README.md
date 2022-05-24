# Course Dart  
Dart is a programming language of google 100% open source Object Oriented.

# Compile and Run 
dart use two types of compile
1) just in time -> when programing 
2) ahead  of time -> when the app is ready 

# Types comments in Dart 
-Line ->   //Hola mundo
Block 
/*
* Este es mi primer 
* hola mundo
* */

# NOTE 
we must always declare the data type, but we can also use dynamic, var, final and conts;

# Dynamic
With the use of dynamic not is necesary decalre the data type. Example: 
dynamic puntos = "2000"   
puntos = 2000 
whit dynamic we can change the data type without problem 

# var
With the use of var it is not necessary to declare the data type either, but here no is posible change the data type once declared. Example:
var puntos1 = 2000
puntos1 = 3000

# final 
Whit the use of  final  once declared the data type not is posible change the value of variable. Example 
final puntos2 = 2000; -> this is the final value, not is posible change the value;
but not is 100% inmutable because when use arrays, we can add a new values 


# const
is similar to final but const is 100% inmutable, here we can't add a new values

# segurity null in variables Dart
for declared a null variable, later of the data type add ?. Exmaple:
int edad? = null;

# type conversation
int 
int.parse("22"):

double 
double.parse("22.50");

String 
300.toString();

note -> bool not is possible of converted

# Concatenation and Interpolation
Concatenation -> print("hola " + "mundo"); Witn the operator +
Interpolation -> print("hola $mundo") ; With the operator $,also to access all the options of the variable we can do it in the following way -> print("hola ${mundo.length}"); With ${}

# escape characters and line break 
To escape characters with \ .Example:
print("\$100") 

To line break with \n . Example:
print("Hola \n bienvenido");

other way is use ''' in the start and final. Example:
print('''Hola este es un ejemplo 
para estruturar mejor un parrafo
sin complejos''');

# Operators
Comparison operators
Exists 6 types of comparison operators
< menor
> elder 
<= greater than equal
>= lees equal   
== equal 
!= diferent 

# Arithmetic operators
+ addition
- subtraction
/ division 
* miltiplication
% residue
~ return the result without decimals 

asignaciotion and opertaion. Example:
int a = 4;
int b = 6;
a += b   // 10
b -= a   //2 

# Ternary operator
19 ? "codeee" : "other codee"

NOTE -> print(x??10) -> here we assignment  10 if x have a null value.













 
