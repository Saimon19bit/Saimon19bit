jshell> int z = a + b
z ==> 45

jshell> z
z ==> 45

jshell> a+c
$8 ==> 7

jshell> z
z ==> 45

jshell> int fecha 150824
|  Error:
|  ';' expected
|  int fecha 150824
|           ^

jshell> int fecha = 150824
fecha ==> 150824

jshell> fecha
fecha ==> 150824

jshell> int dia = 10
dia ==> 10

jshell> int  mes = 08
|  Error:
|  ';' expected
|  int  mes = 08;
|              ^

jshell> int mes = 08
|  Error:
|  ';' expected
|  int mes = 08;
|             ^

jshell> int anio = 2024
anio ==> 2024

jshell> mes
|  Error:
|  cannot find symbol
|    symbol:   variable mes
|  mes
|  ^-^

jshell> int fecha = 100823
fecha ==> 100823

jshell> fecha
fecha ==> 100823

jshell> 13/3
$21 ==> 4

jshell> 10.0/3
$22 ==> 3.3333333333333335

jshell> 13%3
$23 ==> 1

jshell> 100823/100
$24 ==> 1008

jshell> 1008/100
$25 ==> 10

jshell>

jshell> int empanadas = 15
empanadas ==> 15

jshell> int precio = empanadas / 12 * 3000 + empanadas % 12 * 300
precio ==> 3900

jshell> int fecha = 1008 / 100
fecha ==> 10

jshell> int mes = 1008 % 100
mes ==> 8

jshell> int dia = 1008 / 100
dia ==> 10

jshell> int anio 100823 / 1000
|  Error:
|  ';' expected
|  int anio 100823 / 1000
|          ^

jshell> int anio = 100823 / 1000
anio ==> 100
jshell>

C:\Users\Educacion>jshell
|  Welcome to JShell -- Version 21.0.4
|  For an introduction type: /help intro

jshell> int fecha = 150824
fecha ==> 150824

jshell> dia = fecha/1000
|  Error:
|  cannot find symbol
|    symbol:   variable dia
|  dia = fecha/1000
|  ^-^

jshell> fecha/1000
$2 ==> 150

jshell> fecha/10000
$3 ==> 15

jshell> int dia = fecha/10000
dia ==> 15

jshell> int mes = fecha/10000
mes ==> 15

jshell> int mes = fecha/%0000
|  Error:
|  illegal start of expression
|  int mes = fecha/%0000;
jshell> int anio = fecha%1000
anio ==> 824

jshell> int anio = fecha%100
jshell>

C:\Users\Educacion>jshell
|  Welcome to JShell -- Version 21.0.4
|  For an introduction type: /help intro

jshell> int fecha = 150824
fecha ==> 150824

jshell> int dia{}
|  Error:
|  ';' expected
|  int dia{}
|         ^

jshell> int dia;{}
dia ==> 0

jshell> int dia(){}
|  Error:
|  missing return statement
|  int dia(){}
|           ^^

jshell> int dia(){
   ...>     return fecha/1000}
|  Error:
|  ';' expected
|      return fecha/1000}
|                       ^

jshell> int dia(){
   ...>     return fecha/1000
   ...> }
|  Error:
|  ';' expected
|      return fecha/1000
|                       ^

jshell> int dia(){
   ...>     return; fecha/1000
   ...> }
|  Error:
|  not a statement
|      return; fecha/1000
|              ^--------^
|  Error:
|  ';' expected
|      return; fecha/1000
jshell>

C:\Users\Educacion>jshell
|  Welcome to JShell -- Version 21.0.4
|  For an introduction type: /help intro

jshell> /reset
|  Resetting state.

jshell> int fecha = 100823
fecha ==> 100823

jshell> fecha%10000
$2 ==> 823

jshell> fecha % 10000
$3 ==> 823

jshell> fecha % 100000
$4 ==> 823

jshell> fecha % 1000000
$5 ==> 100823

jshell> /history

/reset
int fecha = 100823
fecha%10000
fecha % 10000
fecha % 100000
fecha % 1000000
/history

jshell> int fecha/10000
|  Error:
|  ';' expected
|  int fecha/10000
|           ^

jshell> fecha/10000
$6 ==> 10

jshell> fecha/1000
$7 ==> 100

jshell> int fechaI = fecha/10000
fechaI ==> 10

jshell> int fechaI = fecha/10000
fechaI ==> 10

jshell> int fechaI = fecha%100
fechaI ==> 23

jshell> int fechaI = fecha % 100 * 10000 + fecha / 100 % 100 * 1000 + fecha / 10000
fechaI ==> 238010

jshell> int fecha2 = 170878
fecha2 ==> 170878

jshell> int fecha2I = fecha2 / 10000
fecha2I ==> 17

jshell> int fecha2I = fecha2 % 100
fecha2I ==> 78

jshell> int fecha2I = fecha2 % 100 * 10000
fecha2I ==> 780000

jshell> Integer a= 129
a ==> 129

jshell> Integer b= 129
b ==> 129

jshell> a==b
$18 ==> false
