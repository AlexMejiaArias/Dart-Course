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
