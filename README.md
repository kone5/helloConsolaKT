# helloConsolaKT
se hace click en tools -> kotlin ->kotlin REPL

# y esto es lo que hicimos en la clase

"C:\Program Files\Android\Android Studio\jre\bin\java.exe" -Dkotlin.repl.ideMode=true -Dfile.encoding=UTF-8 @C:\Users\Kone\AppData\Local\Temp\idea_arg_file457073353
Welcome to Kotlin version 1.5.31-release-550 (JRE 11.0.10+0-b96-7249189)
Type :help for help, :quit for quit

1+1
res0: kotlin.Int = 2

30/10.0
res1: kotlin.Double = 3.0

val 1 : int = 6
error: expecting property name or receiver type
val 1 : int = 6
    ^

val i : int = 5
error: unresolved reference: int
val i : int = 5
        ^

val i : int = 5
 printf(i)
error: unresolved reference: int
val i : int = 5
        ^
error: unresolved reference: printf
printf(i)
^

val x : int =6
 println(x)
error: unresolved reference: int
val x : int =6
        ^
error: overload resolution ambiguity: 
public inline fun println(message: Any?): Unit defined in kotlin.io
public inline fun println(message: Boolean): Unit defined in kotlin.io
public inline fun println(message: Byte): Unit defined in kotlin.io
public inline fun println(message: Char): Unit defined in kotlin.io
public inline fun println(message: CharArray): Unit defined in kotlin.io
public inline fun println(message: Double): Unit defined in kotlin.io
public inline fun println(message: Float): Unit defined in kotlin.io
public inline fun println(message: Int): Unit defined in kotlin.io
public inline fun println(message: Long): Unit defined in kotlin.io
public inline fun println(message: Short): Unit defined in kotlin.io
println(x)
^

val i : Int = 5

val i : Int = 5
 println(i)
5

val I = i.toByte()

println(I)
5

I = 257
error: val cannot be reassigned
I = 257
^
error: the integer literal does not conform to the expected type Byte
I = 257
    ^

I = i
error: val cannot be reassigned
I = i
^
error: type mismatch: inferred type is Int but Byte was expected
I = i
    ^

val I : Int 257
incomplete code

val I : Int = 257

println(I)
257

val b2 : Byte = 100

println(b2)
100

val i3 : int = b2
error: unresolved reference: int
val i3 : int = b2
         ^

val i3 : Int = b2
error: type mismatch: inferred type is Byte but Int was expected
val i3 : Int = b2
               ^

val i4 : Int = b2.toInt()

println(i4)
100

var numeroDeManzanas = 5

println(numeroDeManzanas)
5

var numeroDePlatanos = 12

println(numeroDePlatanos)
12

"Tenemos en la Frutera $numeroDeManzanas" + "y $numeroDePlatanos plstanos"
res25: kotlin.String = Tenemos en la Frutera 5y 12 plstanos

"Tenemos en la Frutera $numeroDeManzanas manzanas" + "y $numeroDePlatanos platanos"
res26: kotlin.String = Tenemos en la Frutera 5 manzanasy 12 platanos

"Tenemos en la Frutera $numeroDeManzanas manzanas" + " y $numeroDePlatanos platanos"
res27: kotlin.String = Tenemos en la Frutera 5 manzanas y 12 platanos

numeroDeManzanas = numeroDePlatanos

println(numeroDeManzanas)
12

"Tenemos en la Frutera $numeroDeManzanas manzanas" + " y $numeroDePlatanos platanos"
res30: kotlin.String = Tenemos en la Frutera 12 manzanas y 12 platanos

lateinit var adapter : posillo
error: unresolved reference: posillo
lateinit var adapter : posillo
                       ^

lateinit var adapter : adapter = posillo
error: 'lateinit' modifier is not allowed on properties with initializer
lateinit var adapter : adapter = posillo
^
error: unresolved reference: adapter
lateinit var adapter : adapter = posillo
                       ^
error: unresolved reference: posillo
lateinit var adapter : adapter = posillo
                                 ^

fun printHello() {
     println("Hola Kotlin")
 }

printHello()
Hola Kotlin

fun colacion() {
     val dia : Int = 20
     val fruta : "arandanos"
     println("Hoy es el día $dia y la colación que se come es $fruta")
 }
error: type expected
    val fruta : "arandanos"
                ^
error: unexpected tokens (use ';' to separate expressions on the same line)
    val fruta : "arandanos"
                 ^

fun colacion() {
     val dia : Int = 20
     val fruta = "arandanos"
     println("Hoy es el día $dia y la colación que se come es $fruta")
 }

colacion()
Hoy es el dï¿½a 20 y la colaciï¿½n que se come es arandanos

fun colacion() {
     val dia : Int = 20
     val fruta = "arandanos"
     println("Hoy es el dia $dia y la colacion que se come es $fruta")
 }

colacion()
Hoy es el dia 20 y la colacion que se come es arandanos

fun colacion() {
     val dia : Int = 5
     val fruta = "peras"
     println("Hoy es el día $dia y la colación que se come es $fruta")
 }

colacion()
Hoy es el dï¿½a 5 y la colaciï¿½n que se come es peras

fun colacion() {
     val dia : Int = 5
     val fruta = "peras"
     println("Hoy es el dia $dia y la colacion que se come es $fruta")
 }

colacion()
Hoy es el dia 5 y la colacion que se come es peras

# segunda clase
"C:\Program Files\Android\Android Studio\jre\bin\java.exe" -Dkotlin.repl.ideMode=true -Dfile.encoding=UTF-8 @C:\Users\Kone\AppData\Local\Temp\idea_arg_file1502567590

There were compilation errors in module hello_consolaKT

Welcome to Kotlin version 1.5.31-release-550 (JRE 11.0.10+0-b96-7249189)
Type :help for help, :quit for quit

val verdadero = true

val falso = false

println(verdadero)
true

println(falso)
false

println(!verdadero)
false

println(!falso)
true

println(verdadero && falso)
false

println(falso || verdadero)
true

val x = null

val y : x.toDouble()
incomplete code

val y : ?x.toDouble()
incomplete code

val y = x.toDouble() : ?0.0
incomplete code

val y = ?x.toDouble() : ?0.0
error: expecting an expression
val y = ?x.toDouble() : ?0.0
       ^
error: property getter or setter expected
val y = ?x.toDouble() : ?0.0
        ^

val y = x?.toDouble() : ?0.0
incomplete code

val numDePeces = 50

val numDePlantas = 23

println(numDePeces)
50

println(numDePlantas)
23

if(numDePeces > numDePlantas){
     println("Acuario sano...")
 }else{
     println("Acuario insalubre")
 }
Acuario sano...

val numDePlantas = 70

println(numDePlantas)
70

if(numDePeces > numDePlantas){
     println("Acuario sano...")
 }else{
     println("Acuario insalubre")
 }
Acuario insalubre

val numDePeces = 50

if(numDePeces == 0){
     println("Acuario vacio...!!!")
 }else if(numDePeces < 40){
     println("Acuario con peces...")
 }else{
     println("Acuario con exceso de peces...")
 }
Acuario con exceso de peces...

val numDePeces = 35

if(numDePeces == 0){
     println("Acuario vacio...!!!")
 }else if(numDePeces < 40){
     println("Acuario con peces...")
 }else{
     println("Acuario con exceso de peces...")
 }
Acuario con peces...

when (numDePeces){
     0 -> println("Acuario vacio...!")
     in 1..39 -> println("Acuario con peces...")
     else -> println("Acuario con exceso de peces...")
 }
Acuario con peces...

val numDePeces = 0

when (numDePeces){
     0 -> println("Acuario vacio...!")
     in 1..39 -> println("Acuario con peces...")
     else -> println("Acuario con exceso de peces...")
 }
Acuario vacio...!

val numDePeces = 17

when (numDePeces){
     0 -> println("Acuario vacio...!")
     in 1..39 -> println("Acuario con peces...")
     else -> println("Acuario con exceso de peces...")
 }
Acuario con peces...

val numDePeces = 50

when (numDePeces){
     0 -> println("Acuario vacio...!")
     in 1..39 -> println("Acuario con peces...")
     else -> println("Acuario con exceso de peces...")
 }
Acuario con exceso de peces...

val curso : List<String> = listof("Ana","Jose","Ivan","Elisa")
error: unresolved reference: listof
val curso : List<String> = listof("Ana","Jose","Ivan","Elisa")
                           ^

val curso : List<String> = list0f("Ana","Jose","Ivan","Elisa")
error: unresolved reference: list0f
val curso : List<String> = list0f("Ana","Jose","Ivan","Elisa")
                           ^

val curso : List<String> = listOf("Ana","Jose","Ivan","Elisa")

println(curso)
[Ana, Jose, Ivan, Elisa]

curso.size
res37: kotlin.Int = 4

curso.first()
res38: kotlin.String = Ana

curso.last()
res39: kotlin.String = Elisa

var clase : mutableList<String> = mutableListOf("Eduardo","Pedro","Rita","Tomas","Elisa","Sergio")
error: unresolved reference: mutableList
var clase : mutableList<String> = mutableListOf("Eduardo","Pedro","Rita","Tomas","Elisa","Sergio")
            ^

var clase = mutableListOf("Eduardo","Pedro","Rita","Tomas","Elisa","Sergio")

println(clase)
[Eduardo, Pedro, Rita, Tomas, Elisa, Sergio]

clase.size
res43: kotlin.Int = 6

clase.last
error: function invocation 'last()' expected
clase.last
      ^

clase.last()
res45: kotlin.String = Sergio

clase.first()
res46: kotlin.String = Eduardo

clase.remove(Elisa)
error: unresolved reference: Elisa
clase.remove(Elisa)
             ^

clase.remove("Elisa")
res48: kotlin.Boolean = true

println(clase)
[Eduardo, Pedro, Rita, Tomas, Sergio]

clase.add("Javier")
res50: kotlin.Boolean = true

clase.add("Killer")
res51: kotlin.Boolean = true

println(clase)
[Eduardo, Pedro, Rita, Tomas, Sergio, Javier, Killer]

clase.last()
res53: kotlin.String = Killer
