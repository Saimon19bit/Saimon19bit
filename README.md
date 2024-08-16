## Hi there 👋

<!--
**Saimon19bit/Saimon19bit** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
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

jshell> a==b
