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

# IF, else, else if 
IF, IF ELSE
void main() {
int calificacion = 10;
int calificacionMin = 6;

  if(calificacion == 10){
    print("Exelente");
  }else if(calificacion == 9){
     print("Muy bien");
  }else if(calificacion == 8){
    print("Bien");
  }else if(calificacion == 7){
    print("Regular");
  }else if(calificacion == 6){
    print("Suficiente");
  }else{
    print("No pasaste");
  }
 
}

IF ELSE
void main() {
int calificacion = 7;
int calificacionMin = 6;

  if(calificacion >= calificacionMin){
    print("pasaste");
  }else{
     print("no pasaste");
  }
 
}

# Switch 
With switch we can't comparations.Examples
  int calificacion = 5;

  switch (calificacion) {
    case 10:
      print("Exelente");
      break;
    case 9:
      print("Muy bien");
      break;
    case 8:
      print("Bien");
      break;
    case 7:
      print("Regular");
      break;
    case 6:
      break;
    default:
      print("No pasaste");
      break;
  }

  # LOOPS
  Allows us to repeat a block of code according to a condition

  - FOR
    print("Tabla del uno");
  for (int i = 1; i <= 10; i++) {
    print("1 * $i = ${i * 1}");
  }

  - FOR INSIDE FOR
  All multiplicacion tables
    for (int j = 1; j <= 10; j++) {
    print("Tabla del $j");
    for (int i = 1; i <= 10; i++) {
      print("$j * $i = ${i * j}");
    }
  }

  # FOR EACH
  String name = "Alexander";
  for(int character in name.codeUnits){
  print(String.fromCharCode(character));
  }

  # WHILE Y DO WHILE
  runs until a condition is met

  - WHILE
    int edad = 12;
  while (edad <= 18) {
    print("Tiene $edad");
    ++edad;
  }

  - DO WHILE
  Do while reun min once 
  void main() {
  int edad = 18;
  bool esMenor = false;
  do {
    if (edad >= 18) {
      print("Es mayor de $edad");
      esMenor = false;
    } else {
      print("tiene $edad");
      esMenor = true;
    }

    ++edad;
  } while (esMenor);
}

# List
  List colores = ["azul", "verde", "rojo", "amarillo", 1];
  print(colores[2]);

 DATA TYPE SPECIFIC

  List<int> numeros = [1, 2, 3, 4, 5, 6];
  print(numeros[2]);

  Remove element
  List colores = ["azul", "verde", "rojo", "amarillo", 1];
  print(colores[2]);
  
  colores.removeAt(2);
  print(colores);

  Edit element
List colores = ["azul", "verde", "rojo", "amarillo", 1];

  
  colores[2]="morado"
  print(colores);














 
